---
ns: MISC
aliases: ["0x9bae5ad2508df078"]
---
## SET_INSTANCE_PRIORITY_MODE

```c
// 0x9BAE5AD2508DF078
void SET_INSTANCE_PRIORITY_MODE(int mode);
```

## mode Values:
| Value | Name |
| --- | --- |
| 0 | Singleplayer |
| 1 | Multiplayer |


tell the game if we're changing between single player and multiplayer, so we can strip out low priority map objects

