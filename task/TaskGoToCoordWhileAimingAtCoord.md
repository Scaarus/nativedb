---
ns: TASK
aliases: ["0x11315ab3385b8ac0"]
---
## TASK_GO_TO_COORD_WHILE_AIMING_AT_COORD

```c
// 0x11315AB3385B8AC0
void TASK_GO_TO_COORD_WHILE_AIMING_AT_COORD(Ped ped, Vector3 GoToCoord, Vector3 AimAtCoord, float MoveBlendRatio, bool Shoot, float TargetDistance, float SlowDistance, bool UseNavMesh, int iNavFlags, bool InstantBlendToAim, int FiringPatternHash);
```

The ped will move to the GoToCoord while aiming at the AimAtCoord

## Values for `iNavFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | No Stopping |
| 2 | Adv Slide To Coord And Achieve Heading At End |
| 4 | Go Far As Possible If Target Navmesh Not Loaded |
| 8 | Allow Swimming Underwater |
| 16 | Keep To Pavements |
| 32 | Never Enter Water |
| 64 | Dont Avoid Objects |
| 512 | Stop Exactly |
| 1024 | Accurate Walkrun Start |
| 2048 | Dont Avoid Peds |
| 4096 | Dont Adjust Target Position |
| 8192 | Suppress Exact Stop |
| 32768 | Pull From Edge Extra |


## Values for `FiringPatternHash`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | 1 Burst (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 2 | 1 Then Aim (Fire 1 Bullet Then Aim For The Duration) |
| 3 | Random Bursts (Fire Random Bursts For The Time, Can Change The Frequency Using Set Ped Shoot Rate) |
| 4 | Clip (Uses Firing Type Default As It'S No Longer A Valid Type) |
| 5 | Continuous (Fires At The Maximum Rate For The Duration, Reloading If The Clips Empty) |


## Parameters
* **ped**: 
* **GoToCoord**: 
* **AimAtCoord**: 
* **MoveBlendRatio**: 
* **Shoot**: 
* **TargetDistance**: (Default value: `0`)
* **SlowDistance**: (Default value: `4`)
* **UseNavMesh**: (Default value: `True`)
* **iNavFlags**: (Default value: `Default`)
* **InstantBlendToAim**: (Default value: `False`)
* **FiringPatternHash**: (Default value: `Firing_Pattern_Full_Auto`)
