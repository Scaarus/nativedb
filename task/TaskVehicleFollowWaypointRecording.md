---
ns: TASK
aliases: ["0x3123faa6db1cf7ed"]
---
## TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING

```c
// 0x3123FAA6DB1CF7ED
void TASK_VEHICLE_FOLLOW_WAYPOINT_RECORDING(Ped ped, Vehicle vehicle, string RecordingName, int Mode, int iStartingProgress, int iFlags, int iTargetProgress, float MaxSpeed, bool DriveInLoop, float fTargetArriveDistance);
```

Tells the specified vehicle to follow the specified waypoint route

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


## iFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Turn To Face Waypoint Heading At End |
| 2 | Navmesh To Initial Waypoint |
| 4 | Navmesh Back To Waypoint If Left Route |
| 8 | Start From Closest Point |
| 16 | Vehicles Use Ai Slowdown |
| 32 | Do Not Respond To Collision Events |
| 64 | Do Not Slow For Corners |
| 128 | Start Task Initially Aiming |
| 256 | Start Task Exactstop |
| 512 | Use Tighter Turn Settings |
| 1024 | Allow Steering Around Peds |
| 2048 | Suppress Exactstop |
| 4096 | Slow More For Corners |


A max speed of -1.0 means no speed limit.

