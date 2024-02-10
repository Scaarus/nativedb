---
ns: PATH
aliases: ["0x29c24bfbed8ab8fb"]
---
## GET_APPROX_HEIGHT_FOR_POINT

```c
// 0x29C24BFBED8AB8FB
float GET_APPROX_HEIGHT_FOR_POINT(float x, float y);
```

Returns an approximate height at the 2d coordinate. This is based on a coarse grid compiled from collision data.

X and Y coordinates of the position, where the height will be sampled.

Returns approximate height at the position in meters.

