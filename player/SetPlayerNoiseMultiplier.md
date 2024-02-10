---
ns: PLAYER
aliases: ["0xdb89ef50ff25fce9"]
---
## SET_PLAYER_NOISE_MULTIPLIER

```c
// 0xDB89EF50FF25FCE9
void SET_PLAYER_NOISE_MULTIPLIER(Player player, float Mult);
```

Allows script to control how noisy a player is for AI reaction purposes. This multiplier affects the player while moving normally (not sneaking).

Sets how noisy a player is for AI reaction purposes.


## Parameters
* **player**: 
* **Mult**: 1.0 is the default, > 1.0 is to scale a player to be noisier, < 1.0 scales a player to be quieter.
