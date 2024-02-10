---
ns: TASK
aliases: ["0x04701832b739dce5"]
---
## TASK_GO_TO_ENTITY_WHILE_AIMING_AT_COORD

```c
// 0x04701832B739DCE5
void TASK_GO_TO_ENTITY_WHILE_AIMING_AT_COORD(Ped ped, Entity entity, Vector3 AimAtCoord, float MoveBlendRatio, bool Shoot, float TargetDistance, float SlowDistance, bool UseNavMesh, bool InstantBlendToAim, int FiringPatternHash);
```

The ped will move to the GoToEntityIndex while aiming at the AimAtCoord

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 16 | 1 Burst Uses Firing Type Default As It'S No Longer A Valid Type |
| 17 | 1 Then Aim Fire 1 Bullet Then Aim For The Duration |
| 18 | Random Bursts Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate |
| 19 | Clip Uses Firing Type Default As It'S No Longer A Valid Type |
| 20 | Continuous Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty |

