---
ns: TASK
aliases: ["0xcc665aac360d31e7"]
---
## SET_TASK_VEHICLE_CHASE_BEHAVIOR_FLAG

```c
// 0xCC665AAC360D31E7
void SET_TASK_VEHICLE_CHASE_BEHAVIOR_FLAG(Ped ped, int nFlag, bool Value);
```

```
Sets a behavior flag when chasing a vehicle.

Possible values for nFlag:
| Index | Name |
| --- | --- |
| 1 | Cant Block |
| 2 | Cant Block From Pursue |
| 4 | Cant Pursue |
| 8 | Cant Ram |
| 16 | Cant Spin Out |
| 32 | Cant Make Aggressive Move |
| 64 | Cant Cruise In Front During Block |
| 128 | Use Continuous Ram |
| 256 | Cant Pull Alongside |
| 512 | Cant Pull Alongside Infront |


Sets a behavior flag when chasing a vehicle. The ped must be running TASK_VEHICLE_CHASE.
```
