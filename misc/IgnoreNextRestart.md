---
ns: MISC
aliases: ["0x21ffb63d8c615361"]
---
## IGNORE_NEXT_RESTART

```c
// 0x21FFB63D8C615361
void IGNORE_NEXT_RESTART(bool Ignore);
```

Use in conjunction with [`PAUSE_DEATH_ARREST_RESTART`](#_0x2C2B3493FBF51C71). If the player is killed or arrested and chooses to replay the mission then call IGNORE_NEXT_RESTART(TRUE) so that he isn't respawned at a hospital or police station. IGNORE_NEXT_RESTART(TRUE) should only ever be called if you know that the player has been killed or arrested. Checking IF NOT IS_PLAYER_PLAYING should be enough for this.

