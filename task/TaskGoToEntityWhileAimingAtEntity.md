---
ns: TASK
aliases: ["0x97465886d35210e9"]
---
## TASK_GO_TO_ENTITY_WHILE_AIMING_AT_ENTITY

```c
// 0x97465886D35210E9
void TASK_GO_TO_ENTITY_WHILE_AIMING_AT_ENTITY(Ped ped, Entity entity, Entity entity, float MoveBlendRatio, bool Shoot, float TargetDistance, float SlowDistance, bool UseNavMesh, bool InstantBlendToAim, int FiringPatternHash);
```

The ped will move to the GoToEntityIndex while aiming at the AimAtEntityIndex

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | 1 Burst (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 2 | 1 Then Aim (Fire 1 Bullet Then Aim For The Duration) |
| 3 | Random Bursts (Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate) |
| 4 | Clip (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 5 | Continuous (Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty) |

