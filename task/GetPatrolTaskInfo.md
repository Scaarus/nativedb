---
ns: TASK
aliases: ["0x52f734cebe20dfba"]
---
## GET_PATROL_TASK_INFO

```c
// 0x52F734CEBE20DFBA
bool GET_PATROL_TASK_INFO(Ped ped, int TimeLeftAtNode, int NodeId);
```

Will get info from peds patrol task about the route.

The values it returns should be only checked if the function returns true. The function returns TRUE when the ped has the patrol task as his active task. If the ped is patrolling, the function returns true. If the ped then engages in combat the function will return false until he resumes his patrol task


## Parameters
* **ped**: 
* **TimeLeftAtNode**: returns how long the ped has to remain at that node if standing there. e.g. if the node has a duration of 5000ms and he has been standing there for 2000ms this param returns 3000ms. If the ped is between nodes or the node has 0 time then the parameter will return 0.
* **NodeId**: Returns the ID of the node that the ped is standing at or heading to. This the ID of node assigned by the script. If the patrol task can’t find a valid node then the function will return -1.
