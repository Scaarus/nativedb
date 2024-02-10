---
ns: PLAYER
aliases: ["0x020e5f00cda207ba"]
---
## SET_WANTED_LEVEL_MULTIPLIER

```c
// 0x020E5F00CDA207BA
void SET_WANTED_LEVEL_MULTIPLIER();
```

Sets the chance that the player will get a wanted level.
1.0f is the default value and it will automatically be reset when MISSION_HAS_FINISHED is called. A value of 2.0f means that the player’s wanted level will go up twice as fast when he commits crimes.

If you set the wanted multiplier to a low value 0.01 and a cop see you shoot a ped in face you wil still get a wanted level.

