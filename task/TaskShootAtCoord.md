---
ns: TASK
aliases: ["0x46a6cc01e0826106"]
---
## TASK_SHOOT_AT_COORD

```c
// 0x46A6CC01E0826106
void TASK_SHOOT_AT_COORD(int Duration, int FiringType);
```

Tells the ped to shoot at given coord.

## FiringType Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 16 | 1 Burst Uses Firing Type Default As It'S No Longer A Valid Type |
| 17 | 1 Then Aim Fire 1 Bullet Then Aim For The Duration |
| 18 | Random Bursts Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate |
| 19 | Clip Uses Firing Type Default As It'S No Longer A Valid Type |
| 20 | Continuous Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty |


FIRING_TYPE is in commands_task.sch

