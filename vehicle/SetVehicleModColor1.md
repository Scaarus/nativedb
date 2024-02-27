---
ns: VEHICLE
aliases: ["0x43feb945ee7f85b8"]
---
## SET_VEHICLE_MOD_COLOR_1

```c
// 0x43FEB945EE7F85B8
void SET_VEHICLE_MOD_COLOR_1(Vehicle vehicle, int colorType, int baseColIndex, int specColIndex);
```

Sets color 1 to a mod color on the specified vehicle. More...

## Values for `colorType`:
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

