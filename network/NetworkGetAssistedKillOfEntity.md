---
ns: NETWORK
aliases: ["0x83660b734994124d"]
---
## NETWORK_GET_ASSISTED_KILL_OF_ENTITY

```c
// 0x83660B734994124D
bool NETWORK_GET_ASSISTED_KILL_OF_ENTITY(Player player, Entity entity, int damageDealt);
```

Returns true if player with index playerIndexDamager damaged entity with index entityDamaged. also returns the damage dealt by the player.

This command can be used for any physical objects within the game (e.g. cars, peds and objects).

