---
ns: VEHICLE
aliases: ["0x4c241e39b23df959"]
---
## IS_VEHICLE_DRIVEABLE

```c
// 0x4C241E39B23DF959
bool IS_VEHICLE_DRIVEABLE(Vehicle vehicle, bool CheckFire);
```

Checks that the vehicle is fit to be driven.

Will return false for cars on fire if and only if bCheckFire is true.

Must be used before using many of the other vehicle commands.


## Parameters
* **vehicle**: 
* **CheckFire**: (Default value: `False`)
