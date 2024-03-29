---
ns: TASK
aliases: ["0xb8ecd61f531a7b02"]
---
## TASK_GO_TO_COORD_ANY_MEANS_EXTRA_PARAMS_WITH_CRUISE_SPEED

```c
// 0xB8ECD61F531A7B02
void TASK_GO_TO_COORD_ANY_MEANS_EXTRA_PARAMS_WITH_CRUISE_SPEED(Vector3 Position, float MoveBlendRatio, Vehicle vehicle, bool UseLongRangeVehiclePathing, int DrivingFlags, float MaxRangeToShootTargets, float fExtraVehToTargetDistToPreferVeh, float fDriveStraightLineDistance, int iExtraFlags, float fCruiseSpeed, float fTargetArriveDist);
```

Tells a ped to go to a coord by any means.

## Values for `DrivingFlags`:
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


## Values for `iExtraFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Ignore Vehicle Health |
| 2 | Consider All Nearby Vehicles |
| 4 | Proper Is Driveable Check |
| 8 | Remain In Vehicle At Destination |
| 16 | Never Abandon Vehicle |
| 32 | Never Abandon Vehicle If Moving |
| 64 | Use Ai Targeting For Threats |


As above but has an extra param to set initial cruise speed of vehicle. fCruise


## Parameters
* **Position**: 
* **MoveBlendRatio**: 
* **vehicle**: 
* **UseLongRangeVehiclePathing**: (Default value: `False`)
* **DrivingFlags**: (Default value: `Drivingmode_Stopforcars`)
* **MaxRangeToShootTargets**: 
* **fExtraVehToTargetDistToPreferVeh**: (Default value: `0`)
* **fDriveStraightLineDistance**: (Default value: `20`)
* **iExtraFlags**: (Default value: `Default`)
* **fCruiseSpeed**: 
* **fTargetArriveDist**: Distance to target at which vehicle task will quit. Defaulted to 4m. (Default value: `4`)
