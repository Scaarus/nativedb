---
ns: CAMERA
aliases: ["0xe9ea16d6e54cdca4"]
---
## SET_IN_VEHICLE_CAM_STATE_THIS_UPDATE

```c
// 0xE9EA16D6E54CDCA4
void SET_IN_VEHICLE_CAM_STATE_THIS_UPDATE(Vehicle vehicle, int InVehicleState);
```

Sets the camera exit/enter state for vehicles which defines if the follow vehicle or follow ped camera runs.

## Values for `InVehicleState`:
| Value | Name |
| --- | --- |
| 0 | Entering Vehicle |
| 1 | Inside Vehicle |
| 2 | Exiting Vehicle |
| 3 | Outside Vehicle |


VEHICLE_INDEX

To get the camera to interpolate between the follow ped and follow vehicle cameras the intermediate states have to be called. e.g. from ped to vehicle CAM_OUTSIDE_VEHICLE - CAM_ENTERING_VEHICLE - CAM_INSIDE_VEHICLE from vehicle to ped CAM_INSIDE_VEHICLE - CAM_EXITING_VEHICLE - CAM_OUTSIDE_VEHICLE CAM_ENTERING_VEHICLE Gameplay camera in interpolating to the follow vehicle camera CAM_INSIDE_VEHICLE Gampeplay camera is running the follow vehilce camera CAM_EXITING_VEHICLE Gameplay camera is interpolating from the follow vehicle camera to the follow ped camera CAM_OUTSIDE_VEHICLE Gameplay camera is fully running the follow ped camera, dont need to specify a valid vehicle index here.

