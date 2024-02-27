---
ns: VEHICLE
aliases: ["0x1fd09e7390a74d54"]
---
## SET_VEHICLE_HEADLIGHT_SHADOWS

```c
// 0x1FD09E7390A74D54
void SET_VEHICLE_HEADLIGHT_SHADOWS(Vehicle vehicle, int flags);
```

Sets the vehicle headlight shadow flags. see ENUM VEHICLE_HEADLIGHT_SHADOW_FLAGS, for valid values

## Values for `flags`:
| Value | Name |
| --- | --- |
| 0 | NO_HEADLIGHT_SHADOWS |
| 1 | HEADLIGHTS_CAST_DYNAMIC_SHADOWS |
| 2 | HEADLIGHTS_CAST_STATIC_SHADOWS |
| 3 | HEADLIGHTS_CAST_FULL_SHADOWS |


SET_VEHICLE_HEADLIGHT_SHADOWS is in commands_vehicle.sch

