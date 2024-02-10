---
ns: VEHICLE
aliases: ["0xe8d65ca700c9a693"]
---
## GET_VEHICLE_MOD_COLOR_1

```c
// 0xE8D65CA700C9A693
void GET_VEHICLE_MOD_COLOR_1(Vehicle vehicle, int colorType, int baseColIndex, int specColIndex);
```

Returns the type and index of color 1 on the specified vehicle. More...

## colorType Values:
| Value | Name |
| --- | --- |
| 0 | Metallic |
| 277 | Classic |
| 278 | Pearlescent |
| 279 | Matte |
| 280 | Metals |
| 281 | Chrome |
| 282 | Chameleon |
| 283 | None If This Is Set, The Vehicle Doesn'T Use Mod Colors, It Uses The Regular Color System |


specColIndex only applies to MCT_PEARLESCENT

