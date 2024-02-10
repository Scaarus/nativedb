---
ns: ENTITY
aliases: ["0x0267d00af114f17a"]
---
## HAS_ENTITY_CLEAR_LOS_TO_ENTITY_IN_FRONT

```c
// 0x0267D00AF114F17A
bool HAS_ENTITY_CLEAR_LOS_TO_ENTITY_IN_FRONT(Entity entity, Entity entity);
```

Checks if the entity has a clear line of sight to another entity, and the second entity is in a 180 sphere in front of the first. If the 2 entities are peds then the LOS check is done between the heads of the 2 peds.

