---
ns: TASK
aliases: ["0x08da95e8298ae772"]
---
## TASK_SHOOT_AT_ENTITY

```c
// 0x08DA95E8298AE772
void TASK_SHOOT_AT_ENTITY(Entity entity, int Time, int FiringType);
```

Gives a shoot at entity task.

## Values for `FiringType`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | 1 Burst (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 2 | 1 Then Aim (Fire 1 Bullet Then Aim For The Duration) |
| 3 | Random Bursts (Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate) |
| 4 | Clip (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 5 | Continuous (Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty) |


If -1 is passed to Time the ped will never give up on the task.

