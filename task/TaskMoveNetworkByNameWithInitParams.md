---
ns: TASK
aliases: ["0x3d45b0b355c5e0c9"]
---
## TASK_MOVE_NETWORK_BY_NAME_WITH_INIT_PARAMS

```c
// 0x3D45B0B355C5E0C9
void TASK_MOVE_NETWORK_BY_NAME_WITH_INIT_PARAMS(Ped ped, string network, float blendDuration, bool AllowOverrideCloneUpdate, string animDictionary, int flags);
```

Task to start a move network of the type passed When bAllowOverrideCloneUpdate is used in MP the remotely cloned ped will not update in sync with commands sent locally and it is expected that the remote machine will override the update of the clones task signals. This version allows the network to be setup with initial parameters (clipsets, floats and bools).

## flags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 4 | Use Kinematic Physics |
| 8 | Secondary |
| 16 | Use First Person Arm Ik Left |
| 32 | Use First Person Arm Ik Right |


"animDictionary" In network games you may need to inform the move task of the required dictionary so it can be synced and remote players can manage clones and know when the dictionary is ready e.g. arm wrestling

