---
ns: VEHICLE
aliases: ["0xba291848a0815ca9"]
---
## IS_VEHICLE_TYRE_BURST

```c
// 0xBA291848A0815CA9
bool IS_VEHICLE_TYRE_BURST(Vehicle vehicle, int WheelNumber, bool IsBurstToRim);
```

```
Checks if a vehicles tyre is burst

Possible values for WheelNumber:
| Index | Name |
| --- | --- |
| 0 | Car Front Left |
| 52 | Car Front Right |
| 53 | Car Mid Left |
| 54 | Car Mid Right |
| 55 | Car Rear Left |
| 56 | Car Rear Right |
| 57 | Bike Front |
| 58 | Bike Rear |


SC_WHEEL_LIST is in commands_vehicle.sch IsBurstToRim true will return true only when just the rim remains for the tyre
```
