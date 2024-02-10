---
ns: VEHICLE
aliases: ["0x22ac59a870e6a669"]
---
## IS_VEHICLE_SEAT_FREE

```c
// 0x22AC59A870E6A669
bool IS_VEHICLE_SEAT_FREE(Vehicle vehicle, int seat, bool ConsiderPedUsingSeat);
```

```
Checks if the the vehicle is free.

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
```
