---
ns: ENTITY
aliases: ["0xfcdff7b72d23a1ac"]
---
## HAS_ENTITY_CLEAR_LOS_TO_ENTITY

```c
// 0xFCDFF7B72D23A1AC
bool HAS_ENTITY_CLEAR_LOS_TO_ENTITY(Entity entity, Entity entity, int LOSFlags);
```

Checks if the entity has a clear line of sight to another entity. If the 2 entities are peds then the LOS check is done between the heads of the 2 peds.


## Parameters
* **entity**: 
* **entity**: 
* **LOSFlags**: (Default value: `Los_Flags_Los_To_Entity`)
