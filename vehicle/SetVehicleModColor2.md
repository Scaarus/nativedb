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
| 277 | Classic |
| 278 | Pearlescent |
| 279 | Matte |
| 280 | Metals |
| 281 | Chrome |
| 282 | Chameleon |
| 283 | None If This Is Set, The Vehicle Doesn'T Use Mod Colors, It Uses The Regular Color System |


specColIndex only applies to MCT_PEARLESCENT

