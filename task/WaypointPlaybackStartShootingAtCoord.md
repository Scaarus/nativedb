---
ns: TASK
aliases: ["0x057a25cfcc9db671"]
---
## WAYPOINT_PLAYBACK_START_SHOOTING_AT_COORD

```c
// 0x057A25CFCC9DB671
void WAYPOINT_PLAYBACK_START_SHOOTING_AT_COORD(Ped ped, Vector3 vTargetCoords, bool RunAndGun, int FiringPatternHash);
```

Starts the ped shooting at the specified ped or coordinates whilst already following a waypoint-recording bRunAndGun - specifies whether to use "run & gun" to shoot over shoulder whilst running (ie. ped doesn't strafe)

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | 1 Burst (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 2 | 1 Then Aim (Fire 1 Bullet Then Aim For The Duration) |
| 3 | Random Bursts (Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate) |
| 4 | Clip (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 5 | Continuous (Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty) |

