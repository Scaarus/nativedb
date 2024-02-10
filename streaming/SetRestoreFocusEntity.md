---
ns: STREAMING
aliases: ["0x0811381ef5062fec"]
---
## SET_RESTORE_FOCUS_ENTITY

```c
// 0x0811381EF5062FEC
void SET_RESTORE_FOCUS_ENTITY(Entity entity);
```

```
The game focus is used for loading map data, collisions, object population etc. This command overrides it for the specified entity.

Special case - on player switch termination script may want to restore focus to a specific ped rather than the default current player ped
```
