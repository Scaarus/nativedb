---
ns: STREAMING
aliases: ["0x43d1680c6d19a8e9"]
---
## ALLOW_PLAYER_SWITCH_PAN

```c
// 0x43D1680C6D19A8E9
void ALLOW_PLAYER_SWITCH_PAN();
```

script can request a player switch which pauses before the pan, for example if waiting for script requested assets to load etc. This command signals to the player switch system that it is clear to proceed with the pan

allows currently active switch to perform pan (if it was waiting)

