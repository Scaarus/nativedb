---
ns: TASK
aliases: ["0xe70ba7b90f8390dc"]
---
## WAYPOINT_PLAYBACK_START_SHOOTING_AT_PED

```c
// 0xE70BA7B90F8390DC
void WAYPOINT_PLAYBACK_START_SHOOTING_AT_PED(Ped ped, Ped ped, bool RunAndGun, int FiringPatternHash);
```

Starts the ped shooting at the specified ped or coordinates whilst already following a waypoint-recording bRunAndGun - specifies whether to use "run & gun" to shoot over shoulder whilst running (ie. ped doesn't strafe)

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 16 | 1 Burst Uses Firing Type Default As It'S No Longer A Valid Type |
| 17 | 1 Then Aim Fire 1 Bullet Then Aim For The Duration |
| 18 | Random Bursts Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate |
| 19 | Clip Uses Firing Type Default As It'S No Longer A Valid Type |
| 20 | Continuous Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty |

