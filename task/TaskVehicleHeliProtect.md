---
ns: TASK
aliases: ["0x1e09c32048fefd1c"]
---
## TASK_VEHICLE_HELI_PROTECT

```c
// 0x1E09C32048FEFD1C
void TASK_VEHICLE_HELI_PROTECT(Ped ped, Vehicle vehicle, Entity entity, float CruiseSpeed, int mode, float CustomOffset, int MinHeightAboveTerrain, int HeliFlags);
```

Identical to [TASK_VEHICLE_MISSION](#_0x659427E0EF36BCDE) with MISSION_PROTECT mission,

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


## HeliFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Attainrequestedorientation |
| 2 | Dontmodifyorientation |
| 4 | Dontmodifypitch |
| 8 | Dontmodifythrottle |
| 16 | Dontmodifyroll |
| 32 | Landonarrival |
| 64 | Dontdoavoidance |
| 128 | Startengineimmediately |
| 256 | Forceheightmapavoidance |
| 320 | Heightmaponlyavoidance |
| 512 | Dontclampprobestodestination |
| 1024 | Enabletimeslicingwhenpossible |
| 2048 | Circleoppositedirection |
| 4096 | Maintainheightaboveterrain |
| 8192 | Ignorehiddenentitiesduringland |
| 16384 | Disableallheightmapavoidance |


Tells a helicopter to protect another entity.

