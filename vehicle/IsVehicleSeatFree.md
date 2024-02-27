---
ns: VEHICLE
aliases: ["0x22ac59a870e6a669"]
---
## IS_VEHICLE_SEAT_FREE

```c
// 0x22AC59A870E6A669
bool IS_VEHICLE_SEAT_FREE(Vehicle vehicle, int seat, bool ConsiderPedUsingSeat);
```

Checks if the the vehicle is free.

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


## Parameters
* **vehicle**: 
* **seat**: (Default value: `Driver`)
* **ConsiderPedUsingSeat**: (Default value: `False`)
