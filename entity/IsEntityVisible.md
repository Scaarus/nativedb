---
ns: ENTITY
aliases: ["0x47d6f43d77935c75"]
---
## IS_ENTITY_VISIBLE

```c
// 0x47D6F43D77935C75
bool IS_ENTITY_VISIBLE();
```

Checks if an entity's IS_VISIBLE flag is set, i.e. whether it's being explicitly hidden (by code or script) or not. Note that this function returns true for all entities that have their IS_VISIBLE flag set, even those that aren't actually visible from the current camera (i.e. they are outside the view frustum or behind occluders).

