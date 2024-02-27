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


If Time = -1 the ped will never warp to the vehicle.


## Parameters
* **vehicle**: 
* **Time**: (Default value: `Default_Time_Before_Warp`)
* **seat**: (Default value: `Driver`)
* **MoveBlendRatio**: (Default value: `Pedmoveblendratio_Run`)
