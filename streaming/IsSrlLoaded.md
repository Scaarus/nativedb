---
ns: STREAMING
aliases: ["0xd0263801a4c5b0bb"]
---
## IS_SRL_LOADED

```c
// 0xD0263801A4C5B0BB
bool IS_SRL_LOADED();
```

Check to see whether or not the SRL prefetched with [`PREFETCH_SRL`](#_0x3D245789CE12982C) has finished loading all assets for the the cutscene. You should wait with playing back the scripted cutscene until this returns true, or else there might be assets popping in and out.

