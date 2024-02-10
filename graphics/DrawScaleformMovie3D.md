---
ns: GRAPHICS
aliases: ["0x87d51d72255d4e78"]
---
## DRAW_SCALEFORM_MOVIE_3D

```c
// 0x87D51D72255D4E78
void DRAW_SCALEFORM_MOVIE_3D(Scaleform scaleform, Vector3 vPos, Vector3 vRotation, Vector3 vScale, Vector3 vWorldSize, int RotOrder);
```

Renders a scaleform movie to the screen.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |


movie id (retrieved from REQUEST_SCALEFORM_MOVIE), position, xyz rotation angles in degrees, movie scale, size in world space

movies are drawn in order, with the latest drawn on top.

