---
ns: VEHICLE
aliases: ["0xf2bfa0430f0a0fcb"]
---
## SET_VEHICLE_DOOR_CONTROL

```c
// 0xF2BFA0430F0A0FCB
void SET_VEHICLE_DOOR_CONTROL(Vehicle vehicle, int DoorNumber, int DoorStatus, float AngleRatio);
```

Sets a vehicles door to a new state.

## DoorNumber Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 1 | Front Right |
| 2 | Rear Left |
| 3 | Rear Right |
| 4 | Bonnet |
| 5 | Boot |


## DoorStatus Values:
| Value | Name |
| --- | --- |
| 0 | Intact |
| 1 | Swinging Free (1) |
| 2 | Bashed (2) |
| 3 | Bashed And Swinging Free (3) |
| 4 | Missing (4) |
| 5 | No Reset (5) |


SC_DOOR_LIST and DOOR_DAMAGE are in commands_vehicle.sch fAngleRatio should be between (0.0=shut 1.0=open ) or use -1.0 to ignore.

