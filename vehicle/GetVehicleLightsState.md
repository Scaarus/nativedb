---
ns: VEHICLE
aliases: ["0xb91b4c20085bd12f"]
---
## GET_VEHICLE_LIGHTS_STATE

```c
// 0xB91B4C20085BD12F
bool GET_VEHICLE_LIGHTS_STATE();
```

Gets the state of the vehicle's lights
Values returned by parameter; NB I've had to use INTEGERS because script doesn't allow for "BOOL &" parameters The returned values of bLightsOn and bFullBeam will only ever be 0 or 1

Returns FALSE if vehicle does not exist

