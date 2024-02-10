---
ns: PATH
aliases: ["0x8abe8608576d9ce3"]
---
## GET_APPROX_HEIGHT_FOR_AREA

```c
// 0x8ABE8608576D9CE3
float GET_APPROX_HEIGHT_FOR_AREA(float x0, float y0, float x1, float y1);
```

Returns an approximate height for the area, which is the maximum height in that area. This is based on a coarse grid compiled from collision data.

X and Y coordinates of the area minimum and maximum extents where the height will be sampled.

Returns approximate height for the area in meters.

