---
ns: TASK
aliases: ["0xa55547801eb331fc"]
---
## TASK_GO_TO_COORD_AND_AIM_AT_HATED_ENTITIES_NEAR_COORD

```c
// 0xA55547801EB331FC
void TASK_GO_TO_COORD_AND_AIM_AT_HATED_ENTITIES_NEAR_COORD(Ped ped, Vector3 GoToCoord, Vector3 AimNearCoord, float MoveBlendRatio, bool Shoot, float TargetDistance, float SlowDistance, bool UseNavMesh, int iNavFlags, int iTaskFlags, int FiringPatternHash);
```

Will go to the specified coord and aim at hated entites near the given coord

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


## Values for `iTaskFlags`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | At Goto Coord If Target Los Blocked |


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
* **AimNearCoord**: 
* **MoveBlendRatio**: 
* **Shoot**: 
* **TargetDistance**: (Default value: `0`)
* **SlowDistance**: (Default value: `4`)
* **UseNavMesh**: (Default value: `True`)
* **iNavFlags**: (Default value: `Default`)
* **iTaskFlags**: (Default value: `None`)
* **FiringPatternHash**: (Default value: `Firing_Pattern_Full_Auto`)
