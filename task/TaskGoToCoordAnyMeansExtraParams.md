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
