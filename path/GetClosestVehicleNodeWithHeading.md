---
ns: PATH
aliases: ["0xff071fb798b803b0"]
---
## GET_CLOSEST_VEHICLE_NODE_WITH_HEADING

```c
// 0xFF071FB798B803B0
bool GET_CLOSEST_VEHICLE_NODE_WITH_HEADING(Vector3 Position, Vector3 ReturnNearestNodePosition, float ReturnHeading, int nodeFlags, float zMeasureMult, float zTolerance);
```

WIill return if can the closest vehicle node with a heading, to a coord.

## Values for `nodeFlags`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


Can be used to set a car facing in a reasonable direction when it is placed on the car node. The command will return FALSE if no node could be found (probably due to the nodes not being streamed in).


## Parameters
* **Position**: 
* **ReturnNearestNodePosition**: 
* **ReturnHeading**: 
* **nodeFlags**: (Default value: `Include Switched Off Nodes`)
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance. (Default value: `3`)
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in? (Default value: `0`)
