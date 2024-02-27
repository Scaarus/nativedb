---
ns: STREAMING
aliases: ["0x3d245789ce12982c"]
---
## PREFETCH_SRL

```c
// 0x3D245789CE12982C
void PREFETCH_SRL(string cutsceneName);
```

Tells the system to load a streaming request list and load all the assets needed for the first frame of its cutscene. Call this function several seconds before the cutscene is meant to be played, and wait until HAS_SRL_LOADED before beginning the cutscene and calling [`BEGIN_SRL`](#_0x9BADDC94EF83B823).

