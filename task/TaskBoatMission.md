---
ns: TASK
aliases: ["0x15c86013127ce63f"]
---
## TASK_BOAT_MISSION

```c
// 0x15C86013127CE63F
void TASK_BOAT_MISSION(Vehicle vehicle, Vehicle vehicle, Ped ped, Vector3 Position, int Mission, float CruiseSpeed, int mode, float TargetReachedDist, int BoatFlags);
```

Gives the boat a mission.

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


## mode Values:
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


## BoatFlags Values:
| Value | Name |
| --- | --- |
| 1 | Stopatend |
| 2 | Stopatshore |
| 4 | Avoidshore |
| 7 | Defaultsettings |
| 8 | Preferforward |
| 16 | Neverstop |
| 32 | Nevernavmesh |
| 64 | Neverroute |
| 111 | Openoceansettings |
| 128 | Forcebeached |
| 256 | Usewanderroute |
| 512 | Usefleeroute |
| 1024 | Neverpause |
| 1071 | Boattaxisettings |


VEHICLE_INDEX VehicleIndex (The actual plane that will be flown) VEHICLE_INDEX TargetVehicleIndex (If a target vehicle needs to be specified it is done here) PED_INDEX TargetPedIndex (If a target ped needs to be specified it is done here) FLOAT TargetX, TargetY, TargetZ (specify targetcoordinates here in needed.) VEHICLE_MISSION Mission (Mission to be exectuted. ie MISSION_GOTO, MISSION_ATTACK, MISSION_FOLLOW) in commands_vehicle.sch X:\GTA\gta_rage_scripts\include\commands_vehicle.sch FLOAT CruiseSpeed (in ms) FLOAT TargetReachedDist (distance (in meters) at which plane thinks it's arrived.) ALSO used as the hover distance for MISSION_ATTACK and MISSION_CIRCLE INT BoatFlags

