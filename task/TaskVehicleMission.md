---
ns: TASK
aliases: ["0x659427e0ef36bcde"]
---
## TASK_VEHICLE_MISSION

```c
// 0x659427E0EF36BCDE
void TASK_VEHICLE_MISSION(Vehicle vehicle, Vehicle vehicle, int Mission, float CruiseSpeed, int mode, float TargetReachedDist, float StraightLineDist, bool DriveAgainstTraffic);
```

Tells a ped to perform a task when in a vehicle against another vehicle.

## Values for `Mission`:
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


## Values for `mode`:
| Value | Name |
| --- | --- |
| 0 | DF_UseShortCutLinks |
| 1 | DF_StopForCars |
| 2 | DF_StopForPeds |
| 3 | DF_UseSwitchedOffNodes (cruise tasks ignore this anyway--only used for goto's) |
| 4 | DF_SwerveAroundAllCars |
| 5 | DF_PreferNavmeshRoute (if you're going to be primarily driving off road) |
| 6 | DF_PlaneTaxiMode |
| 8 | DF_SteerAroundStationaryCars |
| 16 | DF_SteerAroundPeds |
| 32 | DF_SteerAroundObjects |
| 64 | DF_DontSteerAroundPlayerPed |
| 128 | DF_StopAtLights |
| 256 | DF_GoOffRoadWhenAvoiding |
| 512 | DF_DriveIntoOncomingTraffic |
| 1024 | DF_DriveInReverse |
| 2048 | DF_UseWanderFallbackInsteadOfStraightLine |
| 4096 | DF_AvoidRestrictedAreas |
| 8192 | DF_PreventBackgroundPathfinding |
| 16384 | DF_AdjustCruiseSpeedBasedOnRoadSpeed |
| 262144 | DRIVINGMODE_PLOUGHTHROUGH |
| 262275 | DRIVINGMODE_STOPFORCARS_STRICT |
| 524288 | DF_ChangeLanesAroundObstructions |
| 786468 | DRIVINGMODE_AVOIDCARS_RECKLESS |
| 786469 | DRIVINGMODE_AVOIDCARS |
| 786475 | DRIVINGMODE_STOPFORCARS_IGNORELIGHTS |
| 786597 | DRIVINGMODE_AVOIDCARS_OBEYLIGHTS |
| 786599 | DRIVINGMODE_AVOIDCARS_STOPFORPEDS_OBEYLIGHTS |
| 786603 | DRIVINGMODE_STOPFORCARS |
| 16777216 | DF_ForceStraightLine |
| 33554432 | DF_UseStringPullingAtJunctions |
| 536870912 | DF_AvoidHighways |
| 1073741824 | DF_ForceJoinInRoadDirection |


INT


## Parameters
* **vehicle**: 
* **vehicle**: 
* **Mission**: 
* **CruiseSpeed**: 
* **mode**: 
* **TargetReachedDist**: 
* **StraightLineDist**: (the distance at which the ai switches to heading for the target directly instead of following the nodes) (just like in sa) Use TASK_VEHICLE_MISSION_PED_TARGET to target another ped instead of a vehicle. The task status is the same as that for TASK_VEHICLE_MISSION, i.e. use GET_SCRIPT_TASK_STATUS(a_ped, SCRIPT_TASK_CAR_MISSION, my_status) to check for both commands. To pick default values (recommended) both parameters can be passed in as -1. DriveAgainstTraffic being true allows the car to drive on the opposite side of the road into incoming traffic
* **DriveAgainstTraffic**: (Default value: `True`)
