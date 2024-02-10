---
ns: MISC
aliases: ["0xadcde75e1c60f32d"]
---
## IS_POSITION_OCCUPIED

```c
// 0xADCDE75E1C60F32D
bool IS_POSITION_OCCUPIED(Vector3 CenterPosition, float radius, bool BuildingFlag, bool VehicleFlag, bool PedFlag, bool ObjectFlag, bool DummyFlag, Entity entity, bool CheckAlive);
```

```
Checks if an sphere around the given center point is ocupied by an entity/entities..

ExludedEntityIndex (Optional) allows for an entity that is ignored by the area check. bCheckAlive will only look for living peds if true
```
