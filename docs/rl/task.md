# Taskの一覧

## コマンド


```shell
./isaaclab.bat -p source/standalone/workflows/sb3/train.py --task
```

## 結果

```shell
+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|
                                            Available Environments in
Isaac Lab
                        |
+--------+------------------------------------------------+-----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| S. No. | Task Name                                      | Entry Point
          | Config
                        |
+--------+------------------------------------------------+-----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
|   1    | Isaac-Repose-Cube-Allegro-Direct-v0            |
omni.isaac.lab_tasks.direct.inhand_manipulation:InHandManipulationEnv
| <class 'omni.isaac.lab_tasks.direct.allegro_hand.allegro_hand_env_cfg.AllegroHandEnvCfg'>
                        |
|   2    | Isaac-Ant-Direct-v0                            |
omni.isaac.lab_tasks.direct.ant:AntEnv
          | <class 'omni.isaac.lab_tasks.direct.ant.ant_env.AntEnvCfg'>
                        |
|   3    | Isaac-Velocity-Flat-Anymal-C-Direct-v0         |
omni.isaac.lab_tasks.direct.anymal_c:AnymalCEnv
          | <class
'omni.isaac.lab_tasks.direct.anymal_c.anymal_c_env.AnymalCFlatEnvCfg'>
                        |
|   4    | Isaac-Velocity-Rough-Anymal-C-Direct-v0        |
omni.isaac.lab_tasks.direct.anymal_c:AnymalCEnv
          | <class
'omni.isaac.lab_tasks.direct.anymal_c.anymal_c_env.AnymalCRoughEnvCfg'>
                        |
|   5    | Isaac-Cartpole-Direct-v0                       |
omni.isaac.lab_tasks.direct.cartpole:CartpoleEnv
          | <class
'omni.isaac.lab_tasks.direct.cartpole.cartpole_env.CartpoleEnvCfg'>
                        |
|   6    | Isaac-Cartpole-RGB-Camera-Direct-v0            |
omni.isaac.lab_tasks.direct.cartpole:CartpoleCameraEnv
| <class 'omni.isaac.lab_tasks.direct.cartpole.cartpole_camera_env.CartpoleRGBCameraEnvCfg'>
                        |
|   7    | Isaac-Cartpole-Depth-Camera-Direct-v0          |
omni.isaac.lab_tasks.direct.cartpole:CartpoleCameraEnv
| <class 'omni.isaac.lab_tasks.direct.cartpole.cartpole_camera_env.CartpoleDepthCameraEnvCfg'>
                        |
|   8    | Isaac-Franka-Cabinet-Direct-v0                 |
omni.isaac.lab_tasks.direct.franka_cabinet:FrankaCabinetEnv
| <class 'omni.isaac.lab_tasks.direct.franka_cabinet.franka_cabinet_env.FrankaCabinetEnvCfg'>
                        |
|   9    | Isaac-Humanoid-Direct-v0                       |
omni.isaac.lab_tasks.direct.humanoid:HumanoidEnv
          | <class
'omni.isaac.lab_tasks.direct.humanoid.humanoid_env.HumanoidEnvCfg'>
                        |
|   10   | Isaac-Repose-Cube-Shadow-Direct-v0             |
omni.isaac.lab_tasks.direct.inhand_manipulation:InHandManipulationEnv
| <class 'omni.isaac.lab_tasks.direct.shadow_hand.shadow_hand_env_cfg.ShadowHandEnvCfg'>
                        |
|   11   | Isaac-Repose-Cube-Shadow-OpenAI-FF-Direct-v0   |
omni.isaac.lab_tasks.direct.inhand_manipulation:InHandManipulationEnv
| <class 'omni.isaac.lab_tasks.direct.shadow_hand.shadow_hand_env_cfg.ShadowHandOpenAIEnvCfg'>
                        |
|   12   | Isaac-Repose-Cube-Shadow-OpenAI-LSTM-Direct-v0 |
omni.isaac.lab_tasks.direct.inhand_manipulation:InHandManipulationEnv
| <class 'omni.isaac.lab_tasks.direct.shadow_hand.shadow_hand_env_cfg.ShadowHandOpenAIEnvCfg'>
                        |
|   13   | Isaac-Quadcopter-Direct-v0                     |
omni.isaac.lab_tasks.direct.quadcopter:QuadcopterEnv
| <class 'omni.isaac.lab_tasks.direct.quadcopter.quadcopter_env.QuadcopterEnvCfg'>
                        |
|   14   | Isaac-Humanoid-v0                              |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.classic.humanoid.humanoid_env_cfg.HumanoidEnvCfg'>
                        |
|   15   | Isaac-Ant-v0                                   |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.classic.ant.ant_env_cfg.AntEnvCfg'>
                        |
|   16   | Isaac-Cartpole-v0                              |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.classic.cartpole.cartpole_env_cfg.CartpoleEnvCfg'>
                        |
|   17   | Isaac-Velocity-Flat-Unitree-A1-v0              |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.a1.flat_env_cfg.UnitreeA1FlatEnvCfg'>
                        |
|   18   | Isaac-Velocity-Flat-Unitree-A1-Play-v0         |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.a1.flat_env_cfg.UnitreeA1FlatEnvCfg_PLAY'>
                   |
|   19   | Isaac-Velocity-Rough-Unitree-A1-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.a1.rough_env_cfg.UnitreeA1RoughEnvCfg'>
                      |
|   20   | Isaac-Velocity-Rough-Unitree-A1-Play-v0        |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.a1.rough_env_cfg.UnitreeA1RoughEnvCfg_PLAY'>
                 |
|   21   | Isaac-Velocity-Flat-Anymal-B-v0                |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_b.flat_env_cfg.AnymalBFlatEnvCfg'>
                    |
|   22   | Isaac-Velocity-Flat-Anymal-B-Play-v0           |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_b.flat_env_cfg.AnymalBFlatEnvCfg_PLAY'>
               |
|   23   | Isaac-Velocity-Rough-Anymal-B-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_b.rough_env_cfg.AnymalBRoughEnvCfg'>
                  |
|   24   | Isaac-Velocity-Rough-Anymal-B-Play-v0          |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_b.rough_env_cfg.AnymalBRoughEnvCfg_PLAY'>
             |
|   25   | Isaac-Velocity-Flat-Anymal-C-v0                |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_c.flat_env_cfg.AnymalCFlatEnvCfg'>
                    |
|   26   | Isaac-Velocity-Flat-Anymal-C-Play-v0           |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_c.flat_env_cfg.AnymalCFlatEnvCfg_PLAY'>
               |
|   27   | Isaac-Velocity-Rough-Anymal-C-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_c.rough_env_cfg.AnymalCRoughEnvCfg'>
                  |
|   28   | Isaac-Velocity-Rough-Anymal-C-Play-v0          |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_c.rough_env_cfg.AnymalCRoughEnvCfg_PLAY'>
             |
|   29   | Isaac-Velocity-Flat-Anymal-D-v0                |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_d.flat_env_cfg.AnymalDFlatEnvCfg'>
                    |
|   30   | Isaac-Velocity-Flat-Anymal-D-Play-v0           |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_d.flat_env_cfg.AnymalDFlatEnvCfg_PLAY'>
               |
|   31   | Isaac-Velocity-Rough-Anymal-D-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_d.rough_env_cfg.AnymalDRoughEnvCfg'>
                  |
|   32   | Isaac-Velocity-Rough-Anymal-D-Play-v0          |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.anymal_d.rough_env_cfg.AnymalDRoughEnvCfg_PLAY'>
             |
|   33   | Isaac-Velocity-Flat-Cassie-v0                  |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.cassie.flat_env_cfg.CassieFlatEnvCfg'>
                       |
|   34   | Isaac-Velocity-Flat-Cassie-Play-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.cassie.flat_env_cfg.CassieFlatEnvCfg_PLAY'>
                  |
|   35   | Isaac-Velocity-Rough-Cassie-v0                 |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.cassie.rough_env_cfg.CassieRoughEnvCfg'>
                     |
|   36   | Isaac-Velocity-Rough-Cassie-Play-v0            |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.cassie.rough_env_cfg.CassieRoughEnvCfg_PLAY'>
                |
|   37   | Isaac-Velocity-Rough-G1-v0                     |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.g1.rough_env_cfg.G1RoughEnvCfg'>
                             |
|   38   | Isaac-Velocity-Rough-G1-Play-v0                |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.g1.rough_env_cfg.G1RoughEnvCfg_PLAY'>
                        |
|   39   | Isaac-Velocity-Flat-G1-v0                      |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.g1.flat_env_cfg.G1FlatEnvCfg'>
                               |
|   40   | Isaac-Velocity-Flat-G1-Play-v0                 |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.g1.flat_env_cfg.G1FlatEnvCfg_PLAY'>
                          |
|   41   | Isaac-Velocity-Flat-Unitree-Go1-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go1.flat_env_cfg.UnitreeGo1FlatEnvCfg'>
                      |
|   42   | Isaac-Velocity-Flat-Unitree-Go1-Play-v0        |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go1.flat_env_cfg.UnitreeGo1FlatEnvCfg_PLAY'>
                 |
|   43   | Isaac-Velocity-Rough-Unitree-Go1-v0            |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go1.rough_env_cfg.UnitreeGo1RoughEnvCfg'>
                    |
|   44   | Isaac-Velocity-Rough-Unitree-Go1-Play-v0       |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go1.rough_env_cfg.UnitreeGo1RoughEnvCfg_PLAY'>
               |
|   45   | Isaac-Velocity-Flat-Unitree-Go2-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go2.flat_env_cfg.UnitreeGo2FlatEnvCfg'>
                      |
|   46   | Isaac-Velocity-Flat-Unitree-Go2-Play-v0        |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go2.flat_env_cfg.UnitreeGo2FlatEnvCfg_PLAY'>
                 |
|   47   | Isaac-Velocity-Rough-Unitree-Go2-v0            |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go2.rough_env_cfg.UnitreeGo2RoughEnvCfg'>
                    |
|   48   | Isaac-Velocity-Rough-Unitree-Go2-Play-v0       |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.go2.rough_env_cfg.UnitreeGo2RoughEnvCfg_PLAY'>
               |
|   49   | Isaac-Velocity-Rough-H1-v0                     |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.h1.rough_env_cfg.H1RoughEnvCfg'>
                             |
|   50   | Isaac-Velocity-Rough-H1-Play-v0                |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.h1.rough_env_cfg.H1RoughEnvCfg_PLAY'>
                        |
|   51   | Isaac-Velocity-Flat-H1-v0                      |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.h1.flat_env_cfg.H1FlatEnvCfg'>
                               |
|   52   | Isaac-Velocity-Flat-H1-Play-v0                 |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.h1.flat_env_cfg.H1FlatEnvCfg_PLAY'>
                          |
|   53   | Isaac-Velocity-Flat-Spot-v0                    |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.spot.flat_env_cfg.SpotFlatEnvCfg'>
                           |
|   54   | Isaac-Velocity-Flat-Spot-Play-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.locomotion.velocity.config.spot.flat_env_cfg.SpotFlatEnvCfg_PLAY'>
                      |
|   55   | Isaac-Open-Drawer-Franka-v0                    |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.cabinet.config.franka.joint_pos_env_cfg.FrankaCabinetEnvCfg'>
              |
|   56   | Isaac-Open-Drawer-Franka-Play-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.cabinet.config.franka.joint_pos_env_cfg.FrankaCabinetEnvCfg_PLAY'>
         |
|   57   | Isaac-Open-Drawer-Franka-IK-Abs-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.cabinet.config.franka.ik_abs_env_cfg.FrankaCabinetEnvCfg'>
                 |
|   58   | Isaac-Open-Drawer-Franka-IK-Rel-v0             |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.cabinet.config.franka.ik_rel_env_cfg.FrankaCabinetEnvCfg'>
                 |
|   59   | Isaac-Repose-Cube-Allegro-v0                   |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.inhand.config.allegro_hand.allegro_env_cfg.AllegroCubeEnvCfg'>
             |
|   60   | Isaac-Repose-Cube-Allegro-Play-v0              |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.inhand.config.allegro_hand.allegro_env_cfg.AllegroCubeEnvCfg_PLAY'>
        |
|   61   | Isaac-Repose-Cube-Allegro-NoVelObs-v0          |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.inhand.config.allegro_hand.allegro_env_cfg.AllegroCubeNoVelObsEnvCfg'>
     |
|   62   | Isaac-Repose-Cube-Allegro-NoVelObs-Play-v0     |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.inhand.config.allegro_hand.allegro_env_cfg.AllegroCubeNoVelObsEnvCfg_PLAY'>
|
|   63   | Isaac-Lift-Cube-Franka-v0                      |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.lift.config.franka.joint_pos_env_cfg.FrankaCubeLiftEnvCfg'>
                |
|   64   | Isaac-Lift-Cube-Franka-Play-v0                 |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.lift.config.franka.joint_pos_env_cfg.FrankaCubeLiftEnvCfg_PLAY'>
           |
|   65   | Isaac-Lift-Cube-Franka-IK-Abs-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.lift.config.franka.ik_abs_env_cfg.FrankaCubeLiftEnvCfg'>
                   |
|   66   | Isaac-Lift-Cube-Franka-IK-Rel-v0               |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.lift.config.franka.ik_rel_env_cfg.FrankaCubeLiftEnvCfg'>
                   |
|   67   | Isaac-Reach-Franka-v0                          |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.franka.joint_pos_env_cfg.FrankaReachEnvCfg'>
                  |
|   68   | Isaac-Reach-Franka-Play-v0                     |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.franka.joint_pos_env_cfg.FrankaReachEnvCfg_PLAY'>
             |
|   69   | Isaac-Reach-Franka-IK-Abs-v0                   |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.franka.ik_abs_env_cfg.FrankaReachEnvCfg'>
                     |
|   70   | Isaac-Reach-Franka-IK-Rel-v0                   |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.franka.ik_rel_env_cfg.FrankaReachEnvCfg'>
                     |
|   71   | Isaac-Reach-UR10-v0                            |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.ur_10.joint_pos_env_cfg.UR10ReachEnvCfg'>
                     |
|   72   | Isaac-Reach-UR10-Play-v0                       |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.manipulation.reach.config.ur_10.joint_pos_env_cfg.UR10ReachEnvCfg_PLAY'>
                |
|   73   | Isaac-Navigation-Flat-Anymal-C-v0              |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.navigation.config.anymal_c.navigation_env_cfg.NavigationEnvCfg'>
                        |
|   74   | Isaac-Navigation-Flat-Anymal-C-Play-v0         |
omni.isaac.lab.envs:ManagerBasedRLEnv
          | <class
'omni.isaac.lab_tasks.manager_based.navigation.config.anymal_c.navigation_env_cfg.NavigationEnvCfg_PLAY'>
                   |
+--------+------------------------------------------------+-----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
```
