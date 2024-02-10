---
ns: PLAYER
aliases: ["0xc968670bface42d9"]
---
## HAS_FORCE_CLEANUP_OCCURRED

```c
// 0xC968670BFACE42D9
bool HAS_FORCE_CLEANUP_OCCURRED(int ForceCleanupBitField);
```

```
Tells the game that if a force cleanup "event" that this script is interested in occurs then the script should jump back to the line after the command and continue processing from there.

Using this command with FORCE_CLEANUP_FLAG_PLAYER_KILLED_OR_ARRESTED in a script means that you don't have to check IS_PLAYER_PLAYING in every loop. The command should be called just after SCRIPT and should only appear once in the script. If the player dies or gets arrested later then the script will jump back to this line and return TRUE so you should probably have something like this in your script. SCRIPT IF HAS_FORCE_CLEANUP_OCCURRED(FORCE_CLEANUP_FLAG_PLAYER_KILLED_OR_ARRESTED) MISSION_CLEANUP() or whatever your cleanup function is called ENDIF You can combine flags using the vertical bar to OR the bits like this IF HAS_FORCE_CLEANUP_OCCURRED(FORCE_CLEANUP_FLAG_PLAYER_KILLED_OR_ARRESTED|FORCE_CLEANUP_FLAG_SP_TO_MP) MISSION_CLEANUP() or whatever your cleanup function is called ENDIF The MISSION_CLEANUP routine will then be run whenever the player is killed or arrested, or a script calls FORCE_CLEANUP(FORCE_CLEANUP_FLAG_SP_TO_MP)
```

## Parameters
* **ForceCleanupBitField**: specifies the types of force cleanup "events" that this script will respond to
