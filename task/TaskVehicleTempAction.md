---
ns: TASK
aliases: ["0xc429dceeb339e129"]
---
## TASK_VEHICLE_TEMP_ACTION

```c
// 0xC429DCEEB339E129
void TASK_VEHICLE_TEMP_ACTION(Vehicle vehicle, int Action, int Time);
```

```
Gives the vehicle a temporary action.

Possible values for Action:
| Index | Name |
| --- | --- |
| 0 | None |
| 150 | Wait |
| 151 | Emptytobereused |
| 152 | Reverse |
| 153 | Handbraketurnleft |
| 154 | Handbraketurnright |
| 155 | Handbrakestraight |
| 156 | Turnleft |
| 157 | Turnright |
| 158 | Goforward |
| 159 | Swerveleft |
| 160 | Swerveright |
| 161 | Emptytobereused2 |
| 162 | Reverse Left |
| 163 | Reverse Right |
| 164 | Plane Fly Up |
| 165 | Plane Fly Straight |
| 166 | Plane Sharp Left |
| 167 | Plane Sharp Right |
| 168 | Headon Collision |
| 169 | Swerveleft Stop |
| 170 | Swerveright Stop |
| 171 | Reverse Straight |
| 172 | Boost Use Steering Angle |
| 173 | Brake |
| 174 | Handbraketurnleft Intelligent |
| 175 | Handbraketurnright Intelligent |
| 176 | Handbrakestraight Intelligent |
| 177 | Reverse Straight Hard |
| 178 | Emptytobereused3 |
| 179 | Burnout |
| 180 | Rev Engine |
| 181 | Goforward Hard |
| 182 | Surface Submarine |


TEMPACTION is is commands_vehicle.sch

These should only be used for short actions
```
