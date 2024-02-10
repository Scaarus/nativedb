---
ns: TASK
aliases: ["0x534aeba6e5ed4cab"]
---
## GET_ACTIVE_VEHICLE_MISSION_TYPE

```c
// 0x534AEBA6E5ED4CAB
vehicle_mission GET_ACTIVE_VEHICLE_MISSION_TYPE(Vehicle vehicle);
```

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Cruise 1 |
| 2 | Ram 2 |
| 3 | Block 3 |
| 4 | Goto 4 |
| 5 | Stop 5 |
| 6 | Attack 6 |
| 7 | Follow 7 |
| 8 | Flee 8 |
| 9 | Circle 9 |
| 10 | Escort Left 10 |
| 11 | Escort Right 11 |
| 12 | Escort Rear 12 |
| 13 | Escort Front 13 |
| 14 | Goto Racing 14 |
| 15 | Follow Recording 15 |
| 16 | Police Behaviour 16 |
| 17 | Park Perpendicular 17 |
| 18 | Park Parallel 18 |
| 19 | Land 19 |
| 20 | Land And Wait 20 |
| 21 | Crash 21 |
| 22 | Pull Over 22 |
| 23 | Protect 23 |


Returns the VEHICLE_MISSION enum of the vehicle mission currently being executed by vehIndex. If not a vehicle, or not currently running any mission, returns MISSION_NONE. NOTES: All vehicle mission escort types currently return MISSION_ESCORT_REAR

