---
ns: MISC
aliases: ["0xc906a7dab05c8d2b"]
---
## GET_GROUND_Z_FOR_3D_COORD

```c
// 0xC906A7DAB05C8D2B
bool GET_GROUND_Z_FOR_3D_COORD(Vector3 Position, float ReturnZ, bool waterAsGround, bool ignoreDistToWaterLevelCheck);
```

Trys to store the Z coordinate of the highest ground below the given point.

The command will return TRUE if it finds collision, FALSE if not.

