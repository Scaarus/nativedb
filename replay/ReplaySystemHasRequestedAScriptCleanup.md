---
ns: REPLAY
aliases: ["0x95ab8b5c992c7b58"]
---
## REPLAY_SYSTEM_HAS_REQUESTED_A_SCRIPT_CLEANUP

```c
// 0x95AB8B5C992C7B58
bool REPLAY_SYSTEM_HAS_REQUESTED_A_SCRIPT_CLEANUP();
```

Before the replay system can play back a clip, it requires all scripts to clean up. Call this command every frame in a script such as main.sc When the command returns TRUE, can you start a cleanup routine similar to that done at the beginning of a mission repeat

