---
ns: PATH
aliases: ["0x22d7275a79fe8215"]
---
## GET_NTH_CLOSEST_VEHICLE_NODE_ID

```c
// 0x22D7275A79FE8215
int GET_NTH_CLOSEST_VEHICLE_NODE_ID(Vector3 Position, int NodeNumber, int nodeFlags, float zMeasureMult, float zTolerance);
```

Will return if can the nth ( n = 1 being closest) closest vehicle node (by index), to a coord.

## nodeFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


As [`GET_NTH_CLOSEST_VEHICLE_NODE`](#_0xE50E52416CCF948B)... but returns a node index. This node index MUST be used within this frame as it's validity is not guaranteed outside.


## Parameters
* **Position**: 
* **NodeNumber**: 
* **nodeFlags**: (Default value: `Include Switched Off Nodes`)
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance. (Default value: `3`)
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in? (Default value: `0`)
