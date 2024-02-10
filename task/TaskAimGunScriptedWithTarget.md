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
| 271 | On Crate |
| 272 | Hanging Upside Down |
| 273 | On Rope |
| 274 | Dingy Rpg |
| 275 | Crate Rpg |
| 276 | Crate Buddy |
| 277 | Plane Wing |
| 278 | Bike |


the target or the vector can be nullzero, but one of them needs to valid. if both are valid the vector is used as an offset

