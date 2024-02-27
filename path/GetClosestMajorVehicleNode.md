---
ns: PATH
aliases: ["0x2eabe3b06f58c1be"]
---
## GET_CLOSEST_MAJOR_VEHICLE_NODE

```c
// 0x2EABE3B06F58C1BE
bool GET_CLOSEST_MAJOR_VEHICLE_NODE(Vector3 Position, Vector3 ReturnNearestNodePosition, float zMeasureMult, float zTolerance);
```

WIill return if can the closest vehicle node even if switched off, to a coord.

This is needed for the prostitute script to find a quiet area to park the car.


## Parameters
* **Position**: 
* **ReturnNearestNodePosition**: 
* **zMeasureMult**: how strongly should the difference in Z direction be weighted? 0.0 = ignored completely, 1.0 = the same as 2d distance. Default is 3.0 since we tend to care about height differences more than 2d distance. (Default value: `3`)
* **zTolerance**: how far apart to the Z coords have to be before zMeasureMult kicks in? (Default value: `0`)
