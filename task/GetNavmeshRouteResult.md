---
ns: TASK
aliases: ["0x632e831f382a0fa8"]
---
## GET_NAVMESH_ROUTE_RESULT

```c
// 0x632E831F382A0FA8
int GET_NAVMESH_ROUTE_RESULT(Ped ped);
```

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Task Not Found (On Navmesh Task Was Found On The Ped) |
| 1 | Route Not Yet Tried (The Task Has Not Yet Looked For A Route) |
| 2 | Route Not Found (The Task Has Tried & Failed To Find A Route (Will Keep Trying)) |
| 3 | Route Found (The Task Has Successfully Found A Route) |

Retruns the state of any active TASK_FOLLOW_NAVMESH_TO_COORD task running on the ped

