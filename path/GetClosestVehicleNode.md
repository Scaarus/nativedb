---
ns: PATH
aliases: ["0x240a18690ae96513"]
---
## GET_CLOSEST_VEHICLE_NODE

```c
// 0x240A18690AE96513
bool GET_CLOSEST_VEHICLE_NODE(Vector3 Position, int nodeFlags, float zMeasureMult, float zTolerance);
```

WIill return if can the closest vehicle node to a coord.

## nodeFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


The commands will return FALSE if no node could be found (probably due to the nodes not being streamed in).


## Parameters
* **Position**: 
* **nodeFlags**: 
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance.
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in?
