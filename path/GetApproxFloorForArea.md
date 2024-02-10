---
ns: PATH
aliases: ["0x3599d741c9ac6310"]
---
## GET_APPROX_FLOOR_FOR_AREA

```c
// 0x3599D741C9AC6310
float GET_APPROX_FLOOR_FOR_AREA(float x0, float y0, float x1, float y1);
```

Returns an approximate floor for the area, which is the floor height in that area. This is based on a coarse grid compiled from collision data.

X and Y coordinates of the area minimum and maximum extents where the height will be sampled.

Returns approximate floor for the area in meters.

