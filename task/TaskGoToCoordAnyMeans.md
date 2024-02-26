---
ns: TASK
aliases: ["0x5bc448cb78fa3e88"]
---
## TASK_GO_TO_COORD_ANY_MEANS

```c
// 0x5BC448CB78FA3E88
void TASK_GO_TO_COORD_ANY_MEANS(Vector3 Position, float MoveBlendRatio, Vehicle vehicle, bool UseLongRangeVehiclePathing, int DrivingFlags, float MaxRangeToShootTargets);
```

Tells a ped to go to a coord by any means.

## DrivingFlags Values:
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


If you want the ped to use a specific vehicle to get to the point then use VEHICLE_INDEX VehicleID. Otherwise, set VehicleID to NULL.


## Parameters
* **Position**: 
* **MoveBlendRatio**: 
* **vehicle**: 
* **UseLongRangeVehiclePathing**: Setting to TRUE tells the vehicle to use TASK_VEHICLE_GOTO_COORDS_LONGRANGE--see its notes for more info
* **DrivingFlags**: 
* **MaxRangeToShootTargets**: 
