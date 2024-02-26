---
ns: VEHICLE
aliases: ["0xba291848a0815ca9"]
---
## IS_VEHICLE_TYRE_BURST

```c
// 0xBA291848A0815CA9
bool IS_VEHICLE_TYRE_BURST(Vehicle vehicle, int WheelNumber, bool IsBurstToRim);
```

Checks if a vehicles tyre is burst

## WheelNumber Values:
| Value | Name |
| --- | --- |
| 0 | Car Front Left |
| 1 | Car Front Right |
| 2 | Car Mid Left |
| 3 | Car Mid Right |
| 4 | Car Rear Left |
| 5 | Car Rear Right |
| 6 | Bike Front |
| 7 | Bike Rear |


SC_WHEEL_LIST is in commands_vehicle.sch IsBurstToRim true will return true only when just the rim remains for the tyre

