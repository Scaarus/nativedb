---
ns: VEHICLE
aliases: ["0x83f969aa1ee2a664"]
---
## GET_LAST_PED_IN_VEHICLE_SEAT

```c
// 0x83F969AA1EE2A664
Ped GET_LAST_PED_IN_VEHICLE_SEAT(Vehicle vehicle, int seat);
```

Gets the last ped to use the designated vehicle seat.

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


Cannont use VS_ANY_PASSENGER

