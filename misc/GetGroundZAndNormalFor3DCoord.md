---
ns: MISC
aliases: ["0x8bdc7bfc57a81e76"]
---
## GET_GROUND_Z_AND_NORMAL_FOR_3D_COORD

```c
// 0x8BDC7BFC57A81E76
bool GET_GROUND_Z_AND_NORMAL_FOR_3D_COORD(Vector3 Position);
```

Trys to store the Z coordinate and surface normal of the highest ground below the given point.

The command will return TRUE if it finds collision, FALSE if not.

