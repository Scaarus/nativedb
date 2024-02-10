---
ns: MISC
aliases: ["0x39455bf4f4f55186"]
---
## IS_AREA_OCCUPIED_SLOW

```c
// 0x39455BF4F4F55186
bool IS_AREA_OCCUPIED_SLOW(Vector3 MinPosition, Vector3 MaxPosition, bool BuildingFlag, bool VehicleFlag, bool PedFlag, bool ObjectFlag, bool DummyFlag, Entity entity, bool CheckAlive);
```

Checks if an area is ocupied by an entity/entities..

ExludedEntityIndex (Optional) allows for an entity that is ignored by the area check. bCheckAlive will only look for living peds if true

Only cosinder using this if IS_AREA_OCCUPIED is not working properly. This version is more expensive, but should be more accurate.

