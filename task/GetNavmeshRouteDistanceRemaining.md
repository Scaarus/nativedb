---
ns: TASK
aliases: ["0xc6f5c0bcdc74d62d"]
---
## GET_NAVMESH_ROUTE_DISTANCE_REMAINING

```c
// 0xC6F5C0BCDC74D62D
int GET_NAVMESH_ROUTE_DISTANCE_REMAINING(Ped ped);
```

Query how much distance is remaining on a ped's navmesh route.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Task Not Found (On Navmesh Task Was Found On The Ped) |
| 1 | Route Not Yet Tried (The Task Has Not Yet Looked For A Route) |
| 2 | Route Not Found (The Task Has Tried & Failed To Find A Route (Will Keep Trying)) |
| 3 | Route Found (The Task Has Successfully Found A Route) |

Peds navigate long distances using a series of smaller sub-routes. Only one sub-route is ever stored in the navmesh task. This script function queries that subroute to determine how much distance is left on it. Therefore: **You can only really trust the results of this function if "bThisIsLastRouteSection" returns as TRUE** **Otherwise there may be any number of further sub-route sections remaining, but not yet calcualted.. Be careful!! **

