---
ns: VEHICLE
aliases: ["0xf2bfa0430f0a0fcb"]
---
## SET_VEHICLE_DOOR_CONTROL

```c
// 0xF2BFA0430F0A0FCB
void SET_VEHICLE_DOOR_CONTROL(Vehicle vehicle, int DoorNumber, int DoorStatus, float AngleRatio);
```

```
Sets a vehicles door to a new state.

Possible values for DoorNumber:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


Possible values for DoorStatus:
| Index | Name |
| --- | --- |
| 0 | Intact |
| 141 | Swinging Free 1 |
| 142 | Bashed 2 |
| 143 | Bashed And Swinging Free 3 |
| 144 | Missing 4 |
| 145 | No Reset 5 |


SC_DOOR_LIST and DOOR_DAMAGE are in commands_vehicle.sch fAngleRatio should be between (0.0=shut 1.0=open ) or use -1.0 to ignore.
```
