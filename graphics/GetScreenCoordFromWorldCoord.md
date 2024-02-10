---
ns: GRAPHICS
aliases: ["0x34e82f05df2974f5"]
---
## GET_SCREEN_COORD_FROM_WORLD_COORD

```c
// 0x34E82F05DF2974F5
bool GET_SCREEN_COORD_FROM_WORLD_COORD(Vector3 vWorldPos);
```

Returns a valid point on screen, if either x or y is invalid, this will return false and -1.0 for x and y.

