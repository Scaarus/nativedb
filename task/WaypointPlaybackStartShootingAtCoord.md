---
ns: TASK
aliases: ["0x057a25cfcc9db671"]
---
## WAYPOINT_PLAYBACK_START_SHOOTING_AT_COORD

```c
// 0x057A25CFCC9DB671
void WAYPOINT_PLAYBACK_START_SHOOTING_AT_COORD(Ped ped, Vector3 vTargetCoords, bool RunAndGun, int FiringPatternHash);
```

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 16 | 1 Burst Uses Firing Type Default As It'S No Longer A Valid Type |
| 17 | 1 Then Aim Fire 1 Bullet Then Aim For The Duration |
| 18 | Random Bursts Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate |
| 19 | Clip Uses Firing Type Default As It'S No Longer A Valid Type |
| 20 | Continuous Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty |

