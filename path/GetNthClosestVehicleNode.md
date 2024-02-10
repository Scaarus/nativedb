---
ns: PATH
aliases: ["0xe50e52416ccf948b"]
---
## GET_NTH_CLOSEST_VEHICLE_NODE

```c
// 0xE50E52416CCF948B
bool GET_NTH_CLOSEST_VEHICLE_NODE(Vector3 Position, int NodeNumber, int nodeFlags, float zMeasureMult, float zTolerance);
```

WIill return if can the nth ( n = 1 being closest) closest vehicle node, to a coord.

## nodeFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


VecCoors.Z will be calculated automatically if you give it a value of –100.0 or below. If NodeNumber is 1 then the closest node will be returned (as with the two commands above). If NodeNumber is 2 then the second closest node will be returned and so on. The command will return FALSE if no node could be found (probably due to the nodes not being streamed in).


## Parameters
* **Position**: 
* **NodeNumber**: 
* **nodeFlags**: 
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance.
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in?
