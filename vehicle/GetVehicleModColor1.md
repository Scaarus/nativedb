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
| 1 | Classic |
| 2 | Pearlescent |
| 3 | Matte |
| 4 | Metals |
| 5 | Chrome |
| 6 | Chameleon |
| 7 | None (If This Is Set, The Vehicle Doesn'T Use Mod Colors, It Uses The Regular Color System) |


specColIndex only applies to MCT_PEARLESCENT

