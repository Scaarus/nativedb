---
ns: TASK
aliases: ["0x5bc448cb78fa3e88"]
---
## TASK_GO_TO_COORD_ANY_MEANS

```c
// 0x5BC448CB78FA3E88
void TASK_GO_TO_COORD_ANY_MEANS(Vector3 Position, float MoveBlendRatio, Vehicle vehicle, bool UseLongRangeVehiclePathing, int DrivingFlags, float MaxRangeToShootTargets);
```

```
Tells a ped to go to a coord by any means.

Possible values for DrivingFlags:
| Index | Name |
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


If you want the ped to use a specific vehicle to get to the point then use VEHICLE_INDEX VehicleID. Otherwise, set VehicleID to NULL.
```

## Parameters
* **Position**: 
* **MoveBlendRatio**: 
* **vehicle**: 
* **UseLongRangeVehiclePathing**: Setting to TRUE tells the vehicle to use TASK_VEHICLE_GOTO_COORDS_LONGRANGE--see its notes for more info
* **DrivingFlags**: 
* **MaxRangeToShootTargets**: 
