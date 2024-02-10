---
ns: NETWORK
aliases: ["0x9eca15adfe141431"]
---
## SHUTDOWN_AND_LOAD_MOST_RECENT_SAVE

```c
// 0x9ECA15ADFE141431
bool SHUTDOWN_AND_LOAD_MOST_RECENT_SAVE();
```

```
Attempts to start a new single player game and load the most recent single player savegame. The code must first queue a savegame operation. If that fails then this command will behave like SHUTDOWN_AND_LAUNCH_SINGLE_PLAYER_GAME(). It will also return FALSE. If the savegame operation can be queued then this command will return TRUE. It will take a number of frames to find the most recent save so this command won't be as immediate as SHUTDOWN_AND_LAUNCH_SINGLE_PLAYER_GAME()
```
