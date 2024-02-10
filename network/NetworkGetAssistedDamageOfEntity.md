---
ns: NETWORK
aliases: ["0x4caca84440fa26f6"]
---
## NETWORK_GET_ASSISTED_DAMAGE_OF_ENTITY

```c
// 0x4CACA84440FA26F6
bool NETWORK_GET_ASSISTED_DAMAGE_OF_ENTITY(Player player, Entity entity);
```

Returns true if player with index playerIndexDamager damaged entity with index entityDamaged. also returns the damage dealt by the player.

This command can be used for any physical objects within the game (e.g. cars, peds and objects).

