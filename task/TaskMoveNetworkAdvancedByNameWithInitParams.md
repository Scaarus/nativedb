---
ns: TASK
aliases: ["0x29682e2ccf21e9b5"]
---
## TASK_MOVE_NETWORK_ADVANCED_BY_NAME_WITH_INIT_PARAMS

```c
// 0x29682E2CCF21E9B5
void TASK_MOVE_NETWORK_ADVANCED_BY_NAME_WITH_INIT_PARAMS(Ped ped, string network, Any* initParams, Vector3 vStartPos, Vector3 vStartRot, int RotOrder, float blendDuration, bool AllowOverrideCloneUpdate, string animDictionary, int flags);
```

Task to start a move network of the type passed with custom start pos and orientation When bAllowOverrideCloneUpdate is used in MP the remotely cloned ped will not update in sync with commands sent locally and it is expected that the remote machine will override the update of the clones task signals. This version allows the network to be setup with initial parameters (clipsets, floats and bools).

## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## Values for `flags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 4 | Use Kinematic Physics |
| 8 | Secondary |
| 16 | Use First Person Arm Ik Left |
| 32 | Use First Person Arm Ik Right |


"animDictionary" In network games you may need to inform the move task of the required dictionary so it can be synced and remote players can manage clones and know when the dictionary is ready e.g. arm wrestling


## Parameters
* **ped**: 
* **network**: 
* **initParams**: 
* **vStartPos**: 
* **vStartRot**: 
* **RotOrder**: (Default value: `Yxz`)
* **blendDuration**: (Default value: `0`)
* **AllowOverrideCloneUpdate**: (Default value: `False`)
* **animDictionary**: (Default value: `Null`)
* **flags**: (Default value: `Default`)
