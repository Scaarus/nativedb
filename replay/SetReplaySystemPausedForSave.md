---
ns: REPLAY
aliases: ["0xe058175f8eafe79a"]
---
## SET_REPLAY_SYSTEM_PAUSED_FOR_SAVE

```c
// 0xE058175F8EAFE79A
void SET_REPLAY_SYSTEM_PAUSED_FOR_SAVE(bool Paused);
```

After [`REPLAY_SYSTEM_HAS_REQUESTED_A_SCRIPT_CLEANUP`](#_0x95AB8B5C992C7B58)() returns TRUE for the first time, the replay code gives the scripts a few seconds to clean up before it clears the world. To store Director Mode settings, the scripts may need to trigger an autosave. Call SET_REPLAY_SYSTEM_PAUSED_FOR_SAVE(TRUE) once before triggering the autosave to prevent the replay code from timing out in the middle of the autosave. Be sure to call SET_REPLAY_SYSTEM_PAUSED_FOR_SAVE(FALSE) after the autosave has finished.

