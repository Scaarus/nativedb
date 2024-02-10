---
ns: VEHICLE
aliases: ["0xa01bc64dd4bfbbac"]
---
## GET_IN_VEHICLE_CLIPSET_HASH_FOR_SEAT

```c
// 0xA01BC64DD4BFBBAC
int GET_IN_VEHICLE_CLIPSET_HASH_FOR_SEAT(Vehicle vehicle, int seat);
```

```
Gets the the in vehicle clipset hash of the vehicle seat.

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
