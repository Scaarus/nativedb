---
ns: PATH
aliases: ["0x34f060f4bf92e018"]
---
## SET_PED_PATHS_IN_AREA

```c
// 0x34F060F4BF92E018
void SET_PED_PATHS_IN_AREA(Vector3 MinPosition, Vector3 MaxPosition, bool Active, bool ForceAbortCurrentPath);
```

Sets the ped paths active state in the given area.

All paths are switched on by default

When a path is switched off, no peds will be created on it and peds that already exist will not use this path to get to a destination.


## Parameters
* **MinPosition**: 
* **MaxPosition**: 
* **Active**: 
* **ForceAbortCurrentPath**: avoid possible stalls by forcing any active path request to be aborted use this if there are reports of this command causing brief hangs waiting for navmesh data to be accessible but be aware that if timing-critical pathfinding is occuring, that it can be interruped by this (Default value: `False`)
