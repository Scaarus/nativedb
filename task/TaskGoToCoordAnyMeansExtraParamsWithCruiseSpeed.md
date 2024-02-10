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

## DrivingFlags Values:
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


As above but has an extra param to set initial cruise speed of vehicle. fCruise


## Parameters
* **Position**: 
* **MoveBlendRatio**: 
* **vehicle**: 
* **UseLongRangeVehiclePathing**: 
* **DrivingFlags**: 
* **MaxRangeToShootTargets**: 
* **fExtraVehToTargetDistToPreferVeh**: 
* **fDriveStraightLineDistance**: 
* **iExtraFlags**: 
* **fCruiseSpeed**: 
* **fTargetArriveDist**: Distance to target at which vehicle task will quit. Defaulted to 4m.
