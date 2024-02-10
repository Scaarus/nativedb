---
ns: ENTITY
aliases: ["0x5f9532f3b5cc2551"]
---
## IS_ENTITY_DEAD

```c
// 0x5F9532F3B5CC2551
bool IS_ENTITY_DEAD(Entity entity, bool IgnoreVehicleDrowningIfInvincible);
```

Checks if the entity is dead.

If the enitiy you are checking is a ped, do not use this check if you are going to give the ped a task. Unless you specifially need to know they are dead use IS_PED_INJURED instead. It will also return true if they are dead.

