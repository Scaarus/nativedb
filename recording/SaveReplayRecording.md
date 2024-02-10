---
ns: RECORDING
aliases: ["0x644546ec5287471b"]
---
## SAVE_REPLAY_RECORDING

```c
// 0x644546EC5287471B
bool SAVE_REPLAY_RECORDING();
```

Saves out the current buffer up until that last time a save was called Returns true if a clip has been marked for save, Returns false if the clip that was being saved is less then the minimum length

