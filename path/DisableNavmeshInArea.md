---
ns: PATH
aliases: ["0x4c8872d8cdbe1b8b"]
---
## DISABLE_NAVMESH_IN_AREA

```c
// 0x4C8872D8CDBE1B8B
void DISABLE_NAVMESH_IN_AREA(Vector3 MaxPosition, bool Disable);
```

All navmesh polygons are switched on by default This will disableenable all polygons TOUCING the input area. Since polygons are irregular in size, it means that the area will likely extend somewhat further than the specified minmax extents *When a mission script exits, all areas disabled by that script will be restored to an enabled state* EXTRA

When a navmesh area is disabled, no navigation will occur through this area - peds will walk around

