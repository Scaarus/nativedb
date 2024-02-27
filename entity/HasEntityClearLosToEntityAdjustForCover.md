---
ns: ENTITY
aliases: ["0x394bde2a7bba031e"]
---
## HAS_ENTITY_CLEAR_LOS_TO_ENTITY_ADJUST_FOR_COVER

```c
// 0x394BDE2A7BBA031E
bool HAS_ENTITY_CLEAR_LOS_TO_ENTITY_ADJUST_FOR_COVER(Entity entity, Entity entity, int LOSFlags);
```

Checks if the entity has a clear line of sight to another entity. If the 2 entities are peds then the LOS check is done between the heads of the 2 peds.


## Parameters
* **entity**: 
* **entity**: 
* **LOSFlags**: (Default value: `Los_Flags_Los_To_Entity`)
