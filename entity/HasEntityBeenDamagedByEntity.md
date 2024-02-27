---
ns: ENTITY
aliases: ["0xc86d67d52a707cf8"]
---
## HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY

```c
// 0xC86D67D52A707CF8
bool HAS_ENTITY_BEEN_DAMAGED_BY_ENTITY(Entity entity, Entity entity, bool CheckDamagerVehicle);
```

Returns TRUE if the last thing to damage the given entity was the given damager entity. Will also return true if the damager entity is in a vehicle that damages the first entity but only if CheckDamagerVehicle is left TRUE

Returns TRUE if the last thing to damage the given entity was the given damager entity


## Parameters
* **entity**: 
* **entity**: 
* **CheckDamagerVehicle**: (Default value: `True`)
