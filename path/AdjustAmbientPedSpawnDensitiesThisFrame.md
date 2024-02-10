---
ns: PATH
aliases: ["0xaa76052dda9bfc3e"]
---
## ADJUST_AMBIENT_PED_SPAWN_DENSITIES_THIS_FRAME

```c
// 0xAA76052DDA9BFC3E
void ADJUST_AMBIENT_PED_SPAWN_DENSITIES_THIS_FRAME(int iAdjustment, Vector3 vMin, Vector3 vMax);
```

```
iAdjustment should be a non-zero value between -MAX_PED_DENSITY and +MAX_PED_DENSITY

Causes the "PED DENSITY" in the given axis-aligned box to be boostedreduced by the provided amount. This can be used to cause more or less peds to spawn in a given area, than is set in the navmesh. It will not have any affect upon areas where the ped density is by deafult zero. This command should be called every frame for as long as it is required. Only one such region may be set per frame, an assert will fire if it is set more that once per frame.
```
