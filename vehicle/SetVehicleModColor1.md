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

