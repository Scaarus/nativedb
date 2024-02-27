---
ns: PATH
aliases: ["0xe04b48f2cc926253"]
---
## SET_PED_PATHS_BACK_TO_ORIGINAL

```c
// 0xE04B48F2CC926253
void SET_PED_PATHS_BACK_TO_ORIGINAL(Vector3 PositionMin, Vector3 PositionMax, bool ForceAbortCurrentPath);
```

Sets all ped nodes back to their original state. (as per the map data)

It is not cool to call a [`SET_PED_PATHS_IN_AREA`](#_0x34F060F4BF92E018)(true) to undo a SET_PED_PATHS_IN_AREA(false) because the nodes that were originally off would now be on.


## Parameters
* **PositionMin**: 
* **PositionMax**: 
* **ForceAbortCurrentPath**: avoid possible stalls by forcing any active path request to be aborted use this if there are reports of this command causing brief hangs waiting for navmesh data to be accessible but be aware that if timing-critical pathfinding is occuring, that it can be interruped by this (Default value: `False`)
