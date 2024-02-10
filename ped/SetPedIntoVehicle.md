---
ns: PED
aliases: ["0xf75b0d629e1c063d"]
---
## SET_PED_INTO_VEHICLE

```c
// 0xF75B0D629E1C063D
void SET_PED_INTO_VEHICLE(Ped ped, Vehicle vehicle, int seat);
```

```
Sets a Ped into the releveant seat of the given Vehicle.

Possible values for seat:
| Index | Name |
| --- | --- |
| -2 | Any Passenger |
| -1 | Driver |
| 0 | Front Right |
| 35 | Back Left Back Left |
| 36 | Back Right Back Right |
| 37 | Extra Left 1 |
| 38 | Extra Right 1 |
| 39 | Extra Left 2 |
| 40 | Extra Right 2 |
| 41 | Extra Left 3 |
| 42 | Extra Right 3 |


VEHICLE_SEAT enum is in generic.sch
```
