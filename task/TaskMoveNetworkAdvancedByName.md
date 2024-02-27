---
ns: TASK
aliases: ["0xd5b35bea41919acb"]
---
## TASK_MOVE_NETWORK_ADVANCED_BY_NAME

```c
// 0xD5B35BEA41919ACB
void TASK_MOVE_NETWORK_ADVANCED_BY_NAME(Ped ped, string network, Vector3 vStartPos, Vector3 vStartRot, int RotOrder, float blendDuration, bool AllowOverrideCloneUpdate, string animDictionary, int flags);
```

Task to start a move network of the type passed with custom start pos and orientation When bAllowOverrideCloneUpdate is used in MP the remotely cloned ped will not update in sync with commands sent locally and it is expected that the remote machine will override the update of the clones task signals.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## flags Values:
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
* **vStartPos**: 
* **vStartRot**: 
* **RotOrder**: (Default value: `Yxz`)
* **blendDuration**: (Default value: `0`)
* **AllowOverrideCloneUpdate**: (Default value: `False`)
* **animDictionary**: (Default value: `Null`)
* **flags**: (Default value: `Default`)
