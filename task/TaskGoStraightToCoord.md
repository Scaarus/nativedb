---
ns: TASK
aliases: ["0xd76b57b44f1e6f8b"]
---
## TASK_GO_STRAIGHT_TO_COORD

```c
// 0xD76B57B44F1E6F8B
void TASK_GO_STRAIGHT_TO_COORD(Ped ped, Vector3 Position, int Time, float FinalHeading, float TargetRadius);
```

Tells the ped to go to a coord, without using the navemesh.

if TimeBeforeTeleport is chosen to be -1 the ped will never warp.


## Parameters
* **ped**: 
* **Position**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
* **FinalHeading**: (Default value: `Default_Navmesh_Final_Heading`)
* **TargetRadius**: (Default value: `0`)
