---
ns: VEHICLE
aliases: ["0xbb40dd2270b65366"]
---
## GET_PED_IN_VEHICLE_SEAT

```c
// 0xBB40DD2270B65366
Ped GET_PED_IN_VEHICLE_SEAT(Vehicle vehicle, int seat, bool ConsiderPedUsingSeat);
```

```
Gets the ped in a vehicle seat.

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


Cannont use VS_ANY_PASSENGER
```
