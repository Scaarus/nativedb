---
ns: MISC
aliases: ["0x2c2b3493fbf51c71"]
---
## PAUSE_DEATH_ARREST_RESTART

```c
// 0x2C2B3493FBF51C71
void PAUSE_DEATH_ARREST_RESTART(bool Paused);
```

When the player is killed or arrested, he will be respawned at the closest hospital or police station. If you want to give the player the option to replay a mission then call PAUSE_DEATH_ARREST_RESTART(TRUE) to prevent the respawn taking place immediately. If the player chooses to replay the mission then call [`IGNORE_NEXT_RESTART`](#_0x21FFB63D8C615361)(TRUE) and call PAUSE_DEATH_ARREST_RESTART(FALSE). If the player chooses not to replay then just call PAUSE_DEATH_ARREST_RESTART(FALSE). PAUSE_DEATH_ARREST_RESTART(TRUE) should only ever be called if you know that the player has been killed or arrested. Checking IF NOT IS_PLAYER_PLAYING should be enough for this.

