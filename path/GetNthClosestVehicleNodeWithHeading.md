---
ns: PATH
aliases: ["0x80ca6a8b6c094cc4"]
---
## GET_NTH_CLOSEST_VEHICLE_NODE_WITH_HEADING

```c
// 0x80CA6A8B6C094CC4
bool GET_NTH_CLOSEST_VEHICLE_NODE_WITH_HEADING(Vector3 Position, int NodeNumber, int nodeFlags, float zMeasureMult, float zTolerance);
```

WIill return if can the nth ( n = 1 being closest) closest vehicle node with a heading, to a coord.

## nodeFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


ReturnNumLanes is the total number of lanes of the link (both directions added together)

Returns a heading which can be used to set a car facing in a reasonable direction when it is placed on the car node. The command will return FALSE if no node could be found (probably due to the nodes not being streamed in).


## Parameters
* **Position**: 
* **NodeNumber**: 
* **nodeFlags**: 
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance.
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in?
