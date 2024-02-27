---
ns: VEHICLE
aliases: ["0xa4822f1cf23f4810"]
---
## GENERATE_VEHICLE_CREATION_POS_FROM_PATHS

```c
// 0xA4822F1CF23F4810
bool GENERATE_VEHICLE_CREATION_POS_FROM_PATHS(Vector3 SearchPos, Vector3 Result, Vector3 ResultLinkDir, float DesiredHeading, float DesiredHeadingTolerance, float MinCreationDistance, bool IncludeSwitchedOffNodes, bool NoWater, bool AllowAgainstTraffic);
```

Gets a position to create a new vehicle. Searches outward from the position in targetPos (recommended: pass in local player's position)


## Parameters
* **SearchPos**: Position to search outward from (most of the time you want the local player's position)
* **Result**: Coordinates to spawn a vehicle, passed back by reference
* **ResultLinkDir**: 
* **DesiredHeading**: Try to find a node facing this direction. (Default value: `0`)
* **DesiredHeadingTolerance**: How far away from the desired heading can we be? (Pass in 180 if you don't care) (Default value: `180`)
* **MinCreationDistance**: What's the minimum distance from SearchPos that you'd like a vehicle to spawn? (Default value: `0`)
* **IncludeSwitchedOffNodes**: Search areas not currently switched on (Default value: `False`)
* **NoWater**: TRUE to prevent finding a position in water (Default value: `True`)
* **AllowAgainstTraffic**: (Default value: `True`)
