---
ns: TASK
aliases: ["0x1dd45f9ecfdb1bc9"]
---
## TASK_GO_TO_COORD_ANY_MEANS_EXTRA_PARAMS

```c
// 0x1DD45F9ECFDB1BC9
void TASK_GO_TO_COORD_ANY_MEANS_EXTRA_PARAMS(Vector3 Position, float MoveBlendRatio, Vehicle vehicle, bool UseLongRangeVehiclePathing, int DrivingFlags, float MaxRangeToShootTargets, float fExtraVehToTargetDistToPreferVeh, float fDriveStraightLineDistance, int iExtraFlags, float fWarpTimerMS);
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


## iExtraFlags Values:
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


As above but has an extra param to increase the distance required from vehicle to the target, a separate command because we cannot change existing script function signatures for patching


## Parameters
* **Position**: 
* **MoveBlendRatio**: 
* **vehicle**: 
* **UseLongRangeVehiclePathing**: 
* **DrivingFlags**: 
* **MaxRangeToShootTargets**: 
* **fExtraVehToTargetDistToPreferVeh**: 
* **fDriveStraightLineDistance**: allow script to define the distance at which vehicles switch to straight-line pathfinding; default to same value as in code (20m)
* **iExtraFlags**: bitset of values from the TASK_GO_TO_COORD_ANY_MEANS_FLAGS enumeration
* **fWarpTimerMS**: 
