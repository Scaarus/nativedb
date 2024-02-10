---
ns: GRAPHICS
aliases: ["0xd2936cab8b58fcbd"]
---
## CASCADE_SHADOWS_SET_CASCADE_BOUNDS

```c
// 0xD2936CAB8B58FCBD
void CASCADE_SHADOWS_SET_CASCADE_BOUNDS(int cascadeIndex, bool Enabled, float x, float y, float z, float radiusScale, bool interpolateToDisabled, float interpolationTime);
```

call this to explicitly set a cascade bounds in worldspace - typically get these from rag "Cascade Shadows/Cascade Bounds Adjust (Mouse Track)"

