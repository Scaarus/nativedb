---
ns: VEHICLE
aliases: ["0xbe5c1255a1830ff5"]
---
## SET_VEHICLE_WILL_FORCE_OTHER_VEHICLES_TO_STOP

```c
// 0xBE5C1255A1830FF5
void SET_VEHICLE_WILL_FORCE_OTHER_VEHICLES_TO_STOP(Vehicle vehicle, bool ForceOtherVehiclesToStop);
```

This is used for cases where a car is parked in the middle of the road and you want traffic to queue rather than try and swerve around.

This is a reset flag and needs to be called each frame

Passing TRUE to this command will make Other vehicles always stop behind the vehicle rather than swerving around.

