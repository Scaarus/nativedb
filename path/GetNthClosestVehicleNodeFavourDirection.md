---
ns: PATH
aliases: ["0x45905be8654ae067"]
---
## GET_NTH_CLOSEST_VEHICLE_NODE_FAVOUR_DIRECTION

```c
// 0x45905BE8654AE067
bool GET_NTH_CLOSEST_VEHICLE_NODE_FAVOUR_DIRECTION(Vector3 Position, Vector3 FacePosition, int NodeNumber, Vector3 ReturnNearestNodePosition, float ReturnHeading, int nodeFlags, float zMeasureMult, float zTolerance);
```

WIill return if can the closest vehicle node,tries to return a heading which points the car in the right direction to reach FaceCoors.

## Values for `nodeFlags`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Include Switched Off Nodes |
| 2 | Include Boat Nodes |
| 4 | Ignore Sliplanes |
| 8 | Ignore Switched Off Deadends |


It will always obey one-way streets. If you want your car to go against one-way streets, you have to check to see if it's facing the right direction and rotate the car 180 degrees.


## Parameters
* **Position**: 
* **FacePosition**: 
* **NodeNumber**: 
* **ReturnNearestNodePosition**: 
* **ReturnHeading**: 
* **nodeFlags**: (Default value: `Include Switched Off Nodes`)
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance. (Default value: `3`)
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in? (Default value: `0`)
