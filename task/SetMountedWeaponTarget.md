---
ns: TASK
aliases: ["0xccd892192c6d2bb9"]
---
## SET_MOUNTED_WEAPON_TARGET

```c
// 0xCCD892192C6D2BB9
void SET_MOUNTED_WEAPON_TARGET(Ped ped, Vehicle vehicle, Vector3 Position, int VehicleTaskMode, bool IgnoreTargetVehDeadCheck);
```

```
Possible values for VehicleTaskMode:
| Index | Name |
| --- | --- |
| 0 | Player |
| 1 | Idle |
| 2 | Aim |
| 3 | Fire |
| 4 | Camera |
| 5 | Search |


Used to update a mounted weapon task (instead of constantly clearing and creating a new task) and to update the position
```
