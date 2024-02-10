---
ns: VEHICLE
aliases: ["0x30785d90c956bf35"]
---
## CAN_SHUFFLE_SEAT

```c
// 0x30785D90C956BF35
bool CAN_SHUFFLE_SEAT(Vehicle vehicle, int Seat);
```

## Seat Values:
| Value | Name |
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


Command to check if a ped could shuffle from this seat. This is a bit expensive,

