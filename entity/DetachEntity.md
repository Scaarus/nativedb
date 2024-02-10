---
ns: ENTITY
aliases: ["0x961ac54bf0613f5d"]
---
## DETACH_ENTITY

```c
// 0x961AC54BF0613F5D
void DETACH_ENTITY(Entity entity, bool ApplyVelocity, bool NoCollisionUntilClear);
```

```
Detaches an entity from being attached. ApplyVelocity is not used for peds. bNoCollisionUntilClear is only used for peds and objects.
```

## Parameters
* **entity**: 
* **ApplyVelocity**: 
* **NoCollisionUntilClear**: disables collision between this object and the parent until they are clear of one anotherNATIVE PROC DETACH_ENTITY(ENTITY_INDEX EntityIndex, bool
