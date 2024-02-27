---
ns: MISC
aliases: ["0xa61b4df533dcb56e"]
---
## IS_AREA_OCCUPIED

```c
// 0xA61B4DF533DCB56E
bool IS_AREA_OCCUPIED(Vector3 MinPosition, Vector3 MaxPosition, bool BuildingFlag, bool VehicleFlag, bool PedFlag, bool ObjectFlag, bool DummyFlag, Entity entity, bool CheckAlive);
```

Checks if an area is ocupied by an entity/entities..

ExludedEntityIndex (Optional) allows for an entity that is ignored by the area check. bCheckAlive will only look for living peds if true


## Parameters
* **MinPosition**: 
* **MaxPosition**: 
* **BuildingFlag**: 
* **VehicleFlag**: 
* **PedFlag**: 
* **ObjectFlag**: 
* **DummyFlag**: 
* **entity**: (Default value: `Null`)
* **CheckAlive**: (Default value: `False`)
