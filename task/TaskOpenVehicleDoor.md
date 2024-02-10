---
ns: TASK
aliases: ["0x965791a9a488a062"]
---
## TASK_OPEN_VEHICLE_DOOR

```c
// 0x965791A9A488A062
void TASK_OPEN_VEHICLE_DOOR(Vehicle vehicle, int Time, int seat, float MoveBlendRatio);
```

Tells a ped to open a vehicle door.

## seat Values:
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


If Time = -1 the ped will never warp to the vehicle.

