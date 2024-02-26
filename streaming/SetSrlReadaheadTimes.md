---
ns: STREAMING
aliases: ["0xbeb2d9a1d9a8f55a"]
---
## SET_SRL_READAHEAD_TIMES

```c
// 0xBEB2D9A1D9A8F55A
void SET_SRL_READAHEAD_TIMES(int prestreamMap, int prestreamAssets, int playbackMap, int playbackAssets);
```

Determine how far in advance an SRL streams. By default, it's 3 seconds. Call this right after calling [PREFETCH_SRL](#_0x3D245789CE12982C)().

There are four arguments. Two each for "while prestreaming" vs "while playing back the cutscene", and two each for "loading assets" vs "loading maps". "Assets" are the actual drawables, those can be big, expensive textures and models. "Maps" contain information about what buildings and props there are. -1 for any of those values will use the default.

