---
ns: PED
aliases: ["0xd86d101fcfd00a4b"]
---
## CLEAR_RAGDOLL_BLOCKING_FLAGS

```c
// 0xD86D101FCFD00A4B
void CLEAR_RAGDOLL_BLOCKING_FLAGS(Ped ped, int flags);
```

Re-enables ragdoll reactions from various forms of damage, (see enum RAGDOLL_BLOCKING_FLAGS)

## Values for `flags`:
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


To re-enable ragdoll from bullets and player ped impacts, use RBF_BULLET_IMPACT | RBF_PLAYER_IMPACT


## Parameters
* **ped**: 
* **flags**: (Default value: `Bullet Impact`)
