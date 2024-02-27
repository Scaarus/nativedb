---
ns: VEHICLE
aliases: ["0x81592be4e3878728"]
---
## GET_VEHICLE_MOD_COLOR_2

```c
// 0x81592BE4E3878728
void GET_VEHICLE_MOD_COLOR_2(Vehicle vehicle, int colorType, int baseColIndex);
```

Returns the type and index of color 2 on the specified vehicle. More...

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

