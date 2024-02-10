---
ns: PLAYER
aliases: ["0xb2c1a29588a9f47c"]
---
## SET_PLAYER_SNEAKING_NOISE_MULTIPLIER

```c
// 0xB2C1A29588A9F47C
void SET_PLAYER_SNEAKING_NOISE_MULTIPLIER(Player player, float Mult);
```

```
Allows script to control how noisy a player is for AI reaction purposes. This multiplier affects the player while sneaking.

Sets how noisy a player is while sneaking for AI reaction purposes.
```

## Parameters
* **player**: 
* **Mult**: 1.0 is the default, > 1.0 is to scale a sneaking player to be noiser, < 1.0 scales a player while sneaking to be quieter.
