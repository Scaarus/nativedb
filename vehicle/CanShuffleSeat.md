---
ns: VEHICLE
aliases: ["0x30785d90c956bf35"]
---
## CAN_SHUFFLE_SEAT

```c
// 0x30785D90C956BF35
bool CAN_SHUFFLE_SEAT(Vehicle vehicle, int Seat);
```

## Values for `Seat`:
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


Command to check if a ped could shuffle from this seat. This is a bit expensive,

