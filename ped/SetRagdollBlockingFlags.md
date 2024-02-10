---
ns: PED
aliases: ["0x26695ec767728d84"]
---
## SET_RAGDOLL_BLOCKING_FLAGS

```c
// 0x26695EC767728D84
void SET_RAGDOLL_BLOCKING_FLAGS(Ped ped, int flags);
```

Blocks ragdoll reactions from various forms of damage, (see enum RAGDOLL_BLOCKING_FLAGS)

## flags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Bullet Impact |
| 2 | Vehicle Impact |
| 4 | Fire |
| 8 | Electrocution |
| 16 | Player Impact |
| 32 | Explosion |
| 64 | Impact Object |
| 128 | Melee |
| 256 | Rubber Bullet |
| 512 | Falling |
| 1024 | Water Jet |
| 2048 | Drowning |
| 4096 | Allow Block Dead Ped |
| 8192 | Player Bump |
| 16384 | Player Ragdoll Bump |
| 32768 | Ped Ragdoll Bump |
| 65536 | Vehicle Grab |


To disable ragdoll from bullets and player ped impacts, use RBF_BULLET_IMPACT | RBF_PLAYER_IMPACT

