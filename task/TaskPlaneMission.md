---
ns: TASK
aliases: ["0x23703cd154e83b88"]
---
## TASK_PLANE_MISSION

```c
// 0x23703CD154E83B88
void TASK_PLANE_MISSION(Vehicle vehicle, Vehicle vehicle, Ped ped, Vector3 Position, int Mission, float CruiseSpeed, float TargetReachedDist, float PlaneOrientation, int FlightHeight, int MinHeightAboveTerrain, bool Precise);
```

Gives the plane a mission.

## Mission Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Cruise (1) |
| 2 | Ram (2) |
| 3 | Block (3) |
| 4 | Goto (4) |
| 5 | Stop (5) |
| 6 | Attack (6) |
| 7 | Follow (7) |
| 8 | Flee (8) |
| 9 | Circle (9) |
| 10 | Escort Left (10) |
| 11 | Escort Right (11) |
| 12 | Escort Rear (12) |
| 13 | Escort Front (13) |
| 14 | Goto Racing (14) |
| 15 | Follow Recording (15) |
| 16 | Police Behaviour (16) |
| 17 | Park Perpendicular (17) |
| 18 | Park Parallel (18) |
| 19 | Land (19) |
| 20 | Land And Wait (20) |
| 21 | Crash (21) |
| 22 | Pull Over (22) |
| 23 | Protect (23) |


VEHICLE_INDEX VehicleIndex (The actual plane that will be flown) VEHICLE_INDEX TargetVehicleIndex (If a target vehicle needs to be specified it is done here) PED_INDEX TargetPedIndex (If a target ped needs to be specified it is done here) FLOAT TargetX, TargetY, TargetZ (specify targetcoordinates here in needed.) VEHICLE_MISSION Mission (Mission to be exectuted. ie MISSION_GOTO, MISSION_ATTACK, MISSION_FOLLOW) in commands_vehicle.sch X:\GTA\gta_rage_scripts\include\commands_vehicle.sch FLOAT CruiseSpeed (in ms) FLOAT TargetReachedDist (distance (in meters) at which plane thinks it's arrived.) ALSO used as the hover distance for MISSION_ATTACK and MISSION_CIRCLE FLOAT Orientation (orientation plane tries to be in. (0-360) Use -1 if not bothered. -1 Should be used in 99% of the times) INT FlightHeight (z coordinate the plane tries to maintain. ie 30 == 30 meters above sea level) INT MinHeightAboveTerrain (height in meters that the plane will try to stay above terrain. ie 20 == always tries to stay at least 20 meters above ground.)

