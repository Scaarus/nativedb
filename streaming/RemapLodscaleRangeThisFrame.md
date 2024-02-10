---
ns: STREAMING
aliases: ["0xbed8ca5ff5e04113"]
---
## REMAP_LODSCALE_RANGE_THIS_FRAME

```c
// 0xBED8CA5FF5E04113
void REMAP_LODSCALE_RANGE_THIS_FRAME(float fOldMin, float fOldMax, float fNewMin, float fNewMax);
```

allows us to remap LOD scale range (e.g. from 1.0-9.0 to 0.8-3.2 or whatever)

old range min / max, new range min/max

overrides the LOD scale. for example if you have specific camera FOV behaviour that result in a LOD scale between fOldMin and fOldMax, we take the camera-fov-desired LOD scale and instead calculate a new LOD scale in the range fNewMin to fNewMax.

