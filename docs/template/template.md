# Templateの作成

## 起動直後

HelloWorldをenableの状態でIsaac SIMを起動すると、UIBuilderクラスの'__init__()'が呼び出されます。

## 最小構成のTemplate

```python
import numpy as np
import omni.timeline
import omni.ui as ui
from omni.isaac.ui.element_wrappers import CollapsableFrame, DropDown, FloatField, TextBlock
from omni.isaac.ui.ui_utils import get_style
from omni.isaac.ui.element_wrappers import Button
import omni.usd

class UIBuilder:
    def __init__(self):
        """enableの状態だとIsaac SIMが起動した際に1度呼び出される
        """
        # フレームは、複数のUI要素を含むことができるサブウィンドウです
        self.frames = []

        # UI要素は、omni.isaac.ui.element_wrappers の UIElementWrapper を使用して作成されます
        self.wrapped_ui_elements = []

        # タイムラインにアクセスして、プログラム上で停止/一時停止/再生を制御します
        self._timeline = omni.timeline.get_timeline_interface()

        # __on_init()を呼び出し
        self._on_init()

    def on_menu_callback(self):
        """ツールバーからUIが開かれたときに呼び出されるコールバック。 

        これは、build_ui()の直後に呼び出されます。
        """
        print("on_menu_callback")

    def on_timeline_event(self, event):
        """タイムラインイベント（再生、停止、一時停止）のコールバック

        Args: 
             event (omni.timeline.TimelineEventType): イベントの種類
        """
        #print("on_timeline_event")
        pass

    def on_physics_step(self, step):
        """物理ステップのコールバック。
        物理ステップは、タイムラインが再生されているときにのみ発生します

        Args:
            step (float): 物理ステップのサイズ
        """
        #print("on_physics_step")
        pass

    def on_stage_event(self, event):
        """ステージイベントのコールバック

        Args:
            event (omni.usd.StageEventType): イベントタイプ
        """
        if event.type == int(omni.usd.StageEventType.HIERARCHY_CHANGED):
            print("Hierarchy changed")
        elif event.type == int(omni.usd.StageEventType.SIMULATION_START_PLAY):
            print("Physx Simulation starts playing")
        elif event.type == int(omni.usd.StageEventType.OMNIGRAPH_START_PLAY):
            print("OmniGraph is starting to play")
        elif event.type == int(omni.usd.StageEventType.ANIMATION_START_PLAY):
            print("Timeline starts playing")
        elif event.type == int(omni.usd.StageEventType.ASSETS_LOADING):
            print("Assets are loading")
        elif event.type == int(omni.usd.StageEventType.ASSETS_LOADED):
            print("Assets loaded successfully")
        elif event.type == int(omni.usd.StageEventType.SIMULATION_STOP_PLAY):
            print("Physx Simulation stopped")
        elif event.type == int(omni.usd.StageEventType.OMNIGRAPH_STOP_PLAY):
            print("OmniGraph stopped playing")
        elif event.type == int(omni.usd.StageEventType.ANIMATION_STOP_PLAY):
            print("Timeline stopped")
        else:
            print(f"Unknown stage event: {event.type}, event name: {event.type}")

        pass

    def cleanup(self):
        """
        ステージが閉じられたときや拡張機能がホットリロードされたときに呼び出されます。 
        必要なクリーンアップ処理を行い、アクティブなコールバック関数を削除します。 
        omni.isaac.ui.element_wrappersからインポートされたボタンは、
        クリーンアップ関数を実装しているので、それを呼び出す必要があります。
        """
        print("cleanup")
        for ui_elem in self.wrapped_ui_elements:
            ui_elem.cleanup()

    def build_ui(self):
        """
        カスタムUIツールを構築して、拡張機能を実行します。 
        この関数は、UIウィンドウが閉じて再度開かれるたびに呼び出されます。
        """
        print("build_ui")

        # ボタンUIの作成
        test_map = CollapsableFrame("Test Controls", collapsed=False)

        with test_map:
            with ui.VStack(style=get_style(), spacing=5, height=0):
                with ui.VStack():
                    road_button = Button(
                        "Test button",
                        "TEST",
                        on_click_fn=self._on_test_clicked,
                    )

                self.wrapped_ui_elements.extend([road_button])

    def _on_test_clicked(self):
        """
        ボタンが押されたら呼ばれる
        """
        print("TEST")

    def _on_init(self):
        print("_on_init")
```


## on_stage_eventで取得できるevent

[https://docs.omniverse.nvidia.com/kit/docs/omni.usd/latest/omni.usd/omni.usd.StageEventType.html](https://docs.omniverse.nvidia.com/kit/docs/omni.usd/latest/omni.usd/omni.usd.StageEventType.html) を参照

