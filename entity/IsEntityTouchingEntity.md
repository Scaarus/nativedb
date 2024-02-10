---
ns: ENTITY
aliases: ["0x17ffc1b2ba35a494"]
---
## IS_ENTITY_TOUCHING_ENTITY

```c
// 0x17FFC1B2BA35A494
bool IS_ENTITY_TOUCHING_ENTITY(Entity entity, Entity entity);
```

```
Checks that 2 entities are intersecting each other this frame. If any of the entities are peds in a vehicle, then the vehicle is used in the check.

This command is only valid for the current frame
```
