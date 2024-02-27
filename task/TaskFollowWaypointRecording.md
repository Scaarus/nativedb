---
ns: TASK
aliases: ["0x0759591819534f7b"]
---
## TASK_FOLLOW_WAYPOINT_RECORDING

```c
// 0x0759591819534F7B
void TASK_FOLLOW_WAYPOINT_RECORDING(Ped ped, string RecordingName, int iStartingProgress, int iFlags, int iTargetProgress);
```

Instructs the ped to follow the named recording, starting at the given waypoint & optionally terminating at a specified waypoint

## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Turn To Face Waypoint Heading At End |
| 2 | Navmesh To Initial Waypoint |
| 4 | Navmesh Back To Waypoint If Left Route |
| 8 | Start From Closest Point |
| 16 | Vehicles Use Ai Slowdown |
| 32 | Do Not Respond To Collision Events |
| 64 | Do Not Slow For Corners |
| 128 | Start Task Initially Aiming |
| 256 | Start Task Exactstop |
| 512 | Use Tighter Turn Settings |
| 1024 | Allow Steering Around Peds |
| 2048 | Suppress Exactstop |
| 4096 | Slow More For Corners |


## Parameters
* **ped**: 
* **RecordingName**: 
* **iStartingProgress**: (Default value: `0`)
* **iFlags**: (Default value: `Default`)
* **iTargetProgress**: 
