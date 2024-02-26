---
ns: GRAPHICS
aliases: ["0x1ce592fdc749d6f5"]
---
## DRAW_SCALEFORM_MOVIE_3D_SOLID

```c
// 0x1CE592FDC749D6F5
void DRAW_SCALEFORM_MOVIE_3D_SOLID(Scaleform scaleform, Vector3 vPos, Vector3 vRotation, Vector3 vScale, Vector3 vWorldSize, int RotOrder);
```

Renders a scaleform movie to the screen (no lighting).

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


movie id (retrieved from [REQUEST_SCALEFORM_MOVIE](#_0x11FE353CF9733E6F)), position, xyz rotation angles in degrees, movie scale, size in world space

movies are drawn in order, with the latest drawn on top.

