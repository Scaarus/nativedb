---
ns: TASK
aliases: ["0x748040460f8df5dc"]
---
## PLAY_ANIM_ON_RUNNING_SCENARIO

```c
// 0x748040460F8DF5DC
void PLAY_ANIM_ON_RUNNING_SCENARIO(Ped ped, string clipSet, string clip);
```

Triggers the passed in clip to play as an animation for the current ped used scenario

clipSet is a clipset not a clip dictionary! This means the string must refer to something in clip_sets.pso.meta. If you do not know how to specify a clipset in data, ask Default AI.

