---
ns: ENTITY
aliases: ["0x9ebc85ed0fffe51c"]
---
## SET_ENTITY_COMPLETELY_DISABLE_COLLISION

```c
// 0x9EBC85ED0FFFE51C
void SET_ENTITY_COMPLETELY_DISABLE_COLLISION(Entity entity, bool UsesCollisionsFlag, bool KeepDisabledSimulatingFlag);
```

Sets if an entity uses any collision at all, this disables exploision and weapon collision as well, added as a seperate command to save updating all scripts.

