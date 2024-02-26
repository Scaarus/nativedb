---
ns: ENTITY
aliases: ["0x621873ece1178967"]
---
## SET_ENTITY_COORDS_WITHOUT_PLANTS_RESET

```c
// 0x621873ECE1178967
void SET_ENTITY_COORDS_WITHOUT_PLANTS_RESET(Entity entity, Vector3 NewPosition, bool DoDeadCheck, bool KeepTasks, bool KeepIK, bool DoWarp);
```

Works exactly like [SET_ENTITY_COORDS](#_0x06843DA7060A026B)() but doesn't reset procedural grass (useful for spectator camera views, etc.)

