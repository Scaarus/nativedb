---
ns: PATH
aliases: ["0x336511a34f2e5185"]
---
## GET_APPROX_FLOOR_FOR_POINT

```c
// 0x336511A34F2E5185
float GET_APPROX_FLOOR_FOR_POINT(float x, float y);
```

Returns an approximate floor at the 2d coordinate. This is based on a coarse grid compiled from collision data.

X and Y coordinates of the position, where the height will be sampled.

Returns approximate floor at the position in meters.

