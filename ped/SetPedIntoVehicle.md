---
ns: PED
aliases: ["0xf75b0d629e1c063d"]
---
## SET_PED_INTO_VEHICLE

```c
// 0xF75B0D629E1C063D
void SET_PED_INTO_VEHICLE(Ped ped, Vehicle vehicle, int seat);
```

Sets a Ped into the releveant seat of the given Vehicle.

## seat Values:
| Value | Name |
| --- | --- |
| -2 | Any Passenger |
| -1 | Driver |
| 0 | Front Right |
| 1 | Back Left (Back Left) |
| 2 | Back Right (Back Right) |
| 3 | Extra Left 1 |
| 4 | Extra Right 1 |
| 5 | Extra Left 2 |
| 6 | Extra Right 2 |
| 7 | Extra Left 3 |
| 8 | Extra Right 3 |


VEHICLE_SEAT enum is in generic.sch


## Parameters
* **ped**: 
* **vehicle**: 
* **seat**: (Default value: `Driver`)
