---
ns: ENTITY
aliases: ["0xdde6df5ae89981d2"]
---
## DOES_ENTITY_BELONG_TO_THIS_SCRIPT

```c
// 0xDDE6DF5AE89981D2
bool DOES_ENTITY_BELONG_TO_THIS_SCRIPT(Entity entity, bool DeadCheck);
```

```
Returns TRUE if the entity is owned by the script thread that called this command. Returns FALSE if the entity is not a script entity or if it is a script entity owned by a different script
```
