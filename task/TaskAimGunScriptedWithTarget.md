---
ns: TASK
aliases: ["0x8605af0de8b3a5ac"]
---
## TASK_AIM_GUN_SCRIPTED_WITH_TARGET

```c
// 0x8605AF0DE8B3A5AC
void TASK_AIM_GUN_SCRIPTED_WITH_TARGET(Ped ped, Vector3 vTargetPosition, int AimGunTaskType, bool DisableGunBlocking, bool ForceAim);
```

Gives a ped a scripted gun task with a target

## AimGunTaskType Values:
| Value | Name |
| --- | --- |
| 0 | On Crate |
| 1 | Hanging Upside Down |
| 2 | On Rope |
| 3 | Dingy Rpg |
| 4 | Crate Rpg |
| 5 | Crate Buddy |
| 6 | Plane Wing |
| 7 | Bike |


the target or the vector can be null/zero, but one of them needs to valid. if both are valid the vector is used as an offset


## Parameters
* **ped**: 
* **vTargetPosition**: 
* **AimGunTaskType**: (Default value: `On Crate`)
* **DisableGunBlocking**: (Default value: `True`)
* **ForceAim**: (Default value: `False`)
