---
ns: CAMERA
aliases: ["0x5c90cab09951a12f"]
---
## SET_FOLLOW_VEHICLE_CAM_SEAT_THIS_UPDATE

```c
// 0x5C90CAB09951A12F
void SET_FOLLOW_VEHICLE_CAM_SEAT_THIS_UPDATE(int seatIndex);
```

Override the gameplay camera seat detection for this update. Useful when we want to switch between a turret and non-turret vehicle camera.


## Parameters
* **seatIndex**: the index of the seat to force
