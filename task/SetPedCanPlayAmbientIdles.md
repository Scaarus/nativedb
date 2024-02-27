---
ns: TASK
aliases: ["0x8fd89a6240813fd0"]
---
## SET_PED_CAN_PLAY_AMBIENT_IDLES

```c
// 0x8FD89A6240813FD0
void SET_PED_CAN_PLAY_AMBIENT_IDLES(Ped ped, bool BlockIdleClips, bool RemoveIdleClipIfPlaying);
```

Blocks/Removes ambient idles from playing on a ped. Must be running TASK_AMBIENT_CLIPS. Must be called every frame to keep blocking/removing (flags get reset every frame to ensure this doesn't get left on accidently).

bBlockIdleClips: if true, blocks future idle clips from playing. bRemoveIdleClipIfPlaying: if true, will remove any current clip playing (will also block).


## Parameters
* **ped**: 
* **BlockIdleClips**: (Default value: `False`)
* **RemoveIdleClipIfPlaying**: (Default value: `False`)
