---
ns: VEHICLE
aliases: ["0xbb40dd2270b65366"]
---
## GET_PED_IN_VEHICLE_SEAT

```c
// 0xBB40DD2270B65366
Ped GET_PED_IN_VEHICLE_SEAT(Vehicle vehicle, int seat, bool ConsiderPedUsingSeat);
```

Gets the ped in a vehicle seat.

## Values for `seat`:
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


Cannont use VS_ANY_PASSENGER


## Parameters
* **vehicle**: 
* **seat**: (Default value: `Driver`)
* **ConsiderPedUsingSeat**: (Default value: `False`)
