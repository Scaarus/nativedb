---
ns: TASK
aliases: ["0xe2a2aa2f659d77a7"]
---
## TASK_VEHICLE_DRIVE_TO_COORD

```c
// 0xE2A2AA2F659D77A7
void TASK_VEHICLE_DRIVE_TO_COORD(Vehicle vehicle, Vector3 Position, float Speed, int Style, Hash modelHash, int Mode, float TargetRadius, float StraightLineDist);
```

Gives a task to drive a vehicle to a coord.

## Style Values:
| Value | Name |
| --- | --- |
| 0 | Straightline |
| 1 | Racing |
| 2 | Reversing |


## Mode Values:
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


CarModel : if the ped can't find the specified vehicle or any other vehicle, a vehicle (with model CarModel) will be automatically created if the ped is off-screen. No vehicle will be created if CarModel is set to DUMMY_MODEL_FOR_SCRIPT. (In San Andreas, passing a CarModel of 1 would use the default car model which was always in memory. This has not been implemented in the Rage code yet.) DRIVINGSTYLE can be found in the DRIVINGSTYLE ENUM in "commands_vehicle.sch" in X:\GTA\gta_rage_scripts\include\ DRIVINGMODE can be found in the DRIVINGMODE ENUM in "commands_vehicle.sch" in X:\GTA\gta_rage_scripts\include\ * If a vehicle is specified and the ped is in the vehicle the ped will just drive to the point. * If a vehicle is specified and the ped isn't in the vehicle then the ped will attempt to get in the vehicle and drive to the point. * If a vehicle is specified and the ped is in another vehicle then ped will get out the car and attempt to get in the correct car and then drive to the point. * If no vehicle is specified then the ped will attempt to get in any nearby vehicle and drive to the point. * If no vehicle is specified and the ped is already in a car then the ped will drive the car to the point. If a ped tries and fails to get in a car

