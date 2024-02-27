---
ns: TASK
aliases: ["0xc429dceeb339e129"]
---
## TASK_VEHICLE_TEMP_ACTION

```c
// 0xC429DCEEB339E129
void TASK_VEHICLE_TEMP_ACTION(Vehicle vehicle, int Action, int Time);
```

Gives the vehicle a temporary action.

## Values for `Action`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Wait |
| 2 | Emptytobereused |
| 3 | Reverse |
| 4 | Handbraketurnleft |
| 5 | Handbraketurnright |
| 6 | Handbrakestraight |
| 7 | Turnleft |
| 8 | Turnright |
| 9 | Goforward |
| 10 | Swerveleft |
| 11 | Swerveright |
| 12 | Emptytobereused2 |
| 13 | Reverse Left |
| 14 | Reverse Right |
| 15 | Plane Fly Up |
| 16 | Plane Fly Straight |
| 17 | Plane Sharp Left |
| 18 | Plane Sharp Right |
| 19 | Headon Collision |
| 20 | Swerveleft Stop |
| 21 | Swerveright Stop |
| 22 | Reverse Straight |
| 23 | Boost Use Steering Angle |
| 24 | Brake |
| 25 | Handbraketurnleft Intelligent |
| 26 | Handbraketurnright Intelligent |
| 27 | Handbrakestraight Intelligent |
| 28 | Reverse Straight Hard |
| 29 | Emptytobereused3 |
| 30 | Burnout |
| 31 | Rev Engine |
| 32 | Goforward Hard |
| 33 | Surface Submarine |


TEMPACTION is is commands_vehicle.sch

These should only be used for short actions

