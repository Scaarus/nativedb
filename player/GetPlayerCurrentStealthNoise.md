---
ns: PLAYER
aliases: ["0x2f395d61f3a1f877"]
---
## GET_PLAYER_CURRENT_STEALTH_NOISE

```c
// 0x2F395D61F3A1F877
float GET_PLAYER_CURRENT_STEALTH_NOISE(Player player);
```

Get an estimate of how much noise a player is making, primarily intended for blipping purposes.

The return value can roughly be considered as a noise range in meters, ramping down over time towards zero.

