---
ns: TASK
aliases: ["0x0fa6e4b75f302400"]
---
## TASK_VEHICLE_ESCORT

```c
// 0x0FA6E4B75F302400
void TASK_VEHICLE_ESCORT(Ped ped, Vehicle vehicle, Entity entity, int EscortType, float CruiseSpeed, int mode, float CustomOffset, int MinHeightAboveTerrain, float StraightLineDistance);
```

Identical to [`TASK_VEHICLE_MISSION`](#_0x659427E0EF36BCDE) with one of the MISSION_ESCORT types, but allows setting a custom offset

## Values for `EscortType`:
| Value | Name |
| --- | --- |
| -1 | Rear |
| 0 | Front |
| 1 | Left |
| 2 | Right |


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


Set CustomOffset to a negative value to use the default

Tells a vehicle to escort another entity.


## Parameters
* **ped**: 
* **vehicle**: 
* **entity**: 
* **EscortType**: 
* **CruiseSpeed**: 
* **mode**: 
* **CustomOffset**: 
* **MinHeightAboveTerrain**: (Default value: `20`)
* **StraightLineDistance**: (Default value: `20`)
