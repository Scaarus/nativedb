---
ns: TASK
aliases: ["0xf0af20aa7731f8c3"]
---
## TASK_VEHICLE_MISSION_COORS_TARGET

```c
// 0xF0AF20AA7731F8C3
void TASK_VEHICLE_MISSION_COORS_TARGET(Vehicle vehicle, Vector3 Position, int Mission, float CruiseSpeed, int mode, float TargetReachedDist, float StraightLineDist, bool DriveAgainstTraffic);
```

Tells a ped in a vehicle to target a coord.

## Mission Values:
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


## mode Values:
| Value | Name |
| --- | --- |
| 1 | F Stopforcars |
| 2 | F Stopforpeds |
| 4 | F Swervearoundallcars |
| 8 | F Steeraroundstationarycars |
| 16 | F Steeraroundpeds |
| 32 | F Steeraroundobjects |
| 64 | F Dontsteeraroundplayerped |
| 128 | F Stopatlights |
| 146 | F Useshortcutlinks |
| 147 | F Useswitchedoffnodes Cruise Tasks Ignore This Anyway--Only Used For Goto'S |
| 148 | F Prefernavmeshroute If You'Re Going To Be Primarily Driving Off Road |
| 149 | F Planetaximode |
| 256 | F Gooffroadwhenavoiding |
| 512 | F Driveintooncomingtraffic |
| 1024 | F Driveinreverse |
| 2048 | F Usewanderfallbackinsteadofstraightline |
| 4096 | F Avoidrestrictedareas |
| 8192 | F Preventbackgroundpathfinding |
| 16384 | F Adjustcruisespeedbasedonroadspeed |
| 262144 | Rivingmode Ploughthrough |
| 262275 | Rivingmode Stopforcars Strict |
| 524288 | F Changelanesaroundobstructions |
| 786468 | Rivingmode Avoidcars Reckless |
| 786469 | Rivingmode Avoidcars |
| 786475 | Rivingmode Stopforcars Ignorelights |
| 786597 | Rivingmode Avoidcars Obeylights |
| 786599 | Rivingmode Avoidcars Stopforpeds Obeylights |
| 786603 | Rivingmode Stopforcars |
| 16777216 | F Forcestraightline |
| 33554432 | F Usestringpullingatjunctions |
| 536870912 | F Avoidhighways |
| 1073741824 | F Forcejoininroaddirection |


:INT TargetReached (the distance at which the ai thinks the target has been reached and the car stops) FLOAT StraightLineDist (the distance at which the ai switches to heading for the target directly instead of following the nodes) (just like in sa) To pick default values (recommended) both parameters can be passed in as -1. Use TASK_CAR_MISSION_PED_TARGET to target another ped instead of a vehicle. The task status is the same as that for TASK_CAR_MISSION, i.e. use GET_SCRIPT_TASK_STATUS(a_ped, SCRIPT_TASK_CAR_MISSION, my_status) to check for both commands. TASK_CAR_MISSION_NOT_AGAINST_TRAFFIC does exaclt the same apart from the fact it won't allow cars to drive against the flow of traffic. TASK_CAR_MISSION does allow cars to drive agains the flow of traffic. DriveAgainstTraffic being true allows the car to drive on the opposite side of the road into incoming traffic
