---
ns: CAMERA
aliases: ["0x9dfe13ecdc1ec196"]
---
## SET_FOLLOW_VEHICLE_CAM_HIGH_ANGLE_MODE_EVERY_UPDATE

```c
// 0x9DFE13ECDC1EC196
void SET_FOLLOW_VEHICLE_CAM_HIGH_ANGLE_MODE_EVERY_UPDATE(bool ShouldOverride, bool Mode);
```

Overrides the state of the high-angle mode for the active follow vehicle camera for every update.

Set to false before the script terminates else this will be on permenantly.


## Parameters
* **ShouldOverride**: 
* **Mode**: HighMode == True , LowMode == False.
