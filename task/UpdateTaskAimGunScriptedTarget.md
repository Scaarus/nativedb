---
ns: TASK
aliases: ["0x9724fb59a3e72ad0"]
---
## UPDATE_TASK_AIM_GUN_SCRIPTED_TARGET

```c
// 0x9724FB59A3E72AD0
void UPDATE_TASK_AIM_GUN_SCRIPTED_TARGET(Ped ped, Vector3 vTargetPosition, bool DisableGunBlocking);
```

Updates a current scripted gun task with a target

the target or the vector can be null/zero, but one of them needs to valid. if both are valid the vector is used as an offset


## Parameters
* **ped**: 
* **vTargetPosition**: 
* **DisableGunBlocking**: (Default value: `True`)
