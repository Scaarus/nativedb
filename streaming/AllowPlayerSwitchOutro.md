---
ns: STREAMING
aliases: ["0x74de2e8739086740"]
---
## ALLOW_PLAYER_SWITCH_OUTRO

```c
// 0x74DE2E8739086740
void ALLOW_PLAYER_SWITCH_OUTRO();
```

```
script can request a player switch which pauses before the outro, for example if waiting for script requested assets to load etc. This command signals to the player switch system that it is clear to proceed with the outro

allows currently active switch to perform outro (if it was waiting)
```
