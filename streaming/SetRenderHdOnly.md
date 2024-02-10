---
ns: STREAMING
aliases: ["0x40aefd1a244741f2"]
---
## SET_RENDER_HD_ONLY

```c
// 0x40AEFD1A244741F2
void SET_RENDER_HD_ONLY(bool hdOnly);
```

```
in very specific circumstances it may be desirable to pre-stream a tiny HD scene and cut to it, and stop the game from trying to draw nearby LODs etc.

Set the game to only render HD models (or not) and strip out all LODs from the scene.
```
