---
ns: VEHICLE
aliases: ["0x816562badfdec83e"]
---
## SET_VEHICLE_MOD_COLOR_2

```c
// 0x816562BADFDEC83E
void SET_VEHICLE_MOD_COLOR_2(Vehicle vehicle, int colorType, int baseColIndex);
```

Sets color 2 to a mod color on the specified vehicle. More...

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

