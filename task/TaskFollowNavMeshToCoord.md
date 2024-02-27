---
ns: TASK
aliases: ["0x15d3a79d4e44b913"]
---
## TASK_FOLLOW_NAV_MESH_TO_COORD

```c
// 0x15D3A79D4E44B913
void TASK_FOLLOW_NAV_MESH_TO_COORD(Ped ped, float MoveBlendRatio, int Time, float Radius, int NavFlags, float FinalHeading);
```

Tells a ped to follow the navmesh to the given coord.

## NavFlags Values:
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


Time is an INT value specifying milliseconds. If the ped has not achieved the target within the allotted time then the ped will be teleported to the target. if Time is chosen to be -1 the ped will never warp.

IMPORTANT NOTE : Sometimes a path may not be able to be found. This could happen because there simply isn't any way to get there, or maybe a bunch of dynamic objects have blocked the way, or maybe the destination is too far away. In this case the ped will simply stand still. To identify when this has happened, you can use [`GET_NAVMESH_ROUTE_RESULT`](#_0x632E831F382A0FA8). This will help you find situations where peds cannot get to their target.


## Parameters
* **ped**: 
* **MoveBlendRatio**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
* **Radius**: (Default value: `Default_Navmesh_Radius`)
* **NavFlags**: (Default value: `Default`)
* **FinalHeading**: (Default value: `Default_Navmesh_Final_Heading`)
