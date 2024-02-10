---
ns: MISC
aliases: ["0xc0aa53f866b3134d"]
---
## FORCE_GAME_STATE_PLAYING

```c
// 0xC0AA53F866B3134D
void FORCE_GAME_STATE_PLAYING();
```

When abandoning a MP session suddenly to return to single player (e.g if the player signed out of their PSN profile) this command force-abandons any active game state such as respawning after death etc, forces to normal play state. Don't use this unless you know exactly why you are using it.

