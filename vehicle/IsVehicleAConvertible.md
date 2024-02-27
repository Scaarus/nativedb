---
ns: VEHICLE
aliases: ["0x52f357a30698bcce"]
---
## IS_VEHICLE_A_CONVERTIBLE

```c
// 0x52F357A30698BCCE
bool IS_VEHICLE_A_CONVERTIBLE(Vehicle vehicle, bool CheckRoofExtras);
```

returns whether the vehicle has a converitble roof and an animation to lower/raise it.

Set CheckRoofExtras to true to also check for roofs without animation (ie. using VEH_EXTRAs)


## Parameters
* **vehicle**: 
* **CheckRoofExtras**: (Default value: `False`)
