---
ns: VEHICLE
aliases: ["0x34e710ff01247c5a"]
---
## SET_VEHICLE_LIGHTS

```c
// 0x34E710FF01247C5A
void SET_VEHICLE_LIGHTS(Vehicle vehicle, int CarLightSetting);
```

Sets the vehicle lights status.

## Values for `CarLightSetting`:
| Value | Name |
| --- | --- |
| 0 | NO_VEHICLE_LIGHT_OVERRIDE |
| 1 | FORCE_VEHICLE_LIGHTS_OFF (1) |
| 2 | FORCE_VEHICLE_LIGHTS_ON (2) |
| 3 | SET_VEHICLE_LIGHTS_ON (3) |
| 4 | SET_VEHICLE_LIGHTS_OFF (4) |


VEHICLE_LIGHT_SETTING is in commands_vehicle.sch

