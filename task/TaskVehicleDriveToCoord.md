---
ns: TASK
aliases: ["0xe2a2aa2f659d77a7"]
---
## TASK_VEHICLE_DRIVE_TO_COORD

```c
// 0xE2A2AA2F659D77A7
void TASK_VEHICLE_DRIVE_TO_COORD(Vehicle vehicle, Vector3 Position, float Speed, int Style, Hash modelHash, int Mode, float TargetRadius, float StraightLineDist);
```

```
Gives a task to drive a vehicle to a coord.

Possible values for Style:
| Index | Name |
| --- | --- |
| 0 | Straightline |
| 1 | Racing |
| 2 | Reversing |


Possible values for Mode:
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


CarModel : if the ped can't find the specified vehicle or any other vehicle, a vehicle (with model CarModel) will be automatically created if the ped is off-screen. No vehicle will be created if CarModel is set to DUMMY_MODEL_FOR_SCRIPT. (In San Andreas, passing a CarModel of 1 would use the default car model which was always in memory. This has not been implemented in the Rage code yet.) DRIVINGSTYLE can be found in the DRIVINGSTYLE ENUM in "commands_vehicle.sch" in X:\GTA\gta_rage_scripts\include\ DRIVINGMODE can be found in the DRIVINGMODE ENUM in "commands_vehicle.sch" in X:\GTA\gta_rage_scripts\include\ * If a vehicle is specified and the ped is in the vehicle the ped will just drive to the point. * If a vehicle is specified and the ped isn't in the vehicle then the ped will attempt to get in the vehicle and drive to the point. * If a vehicle is specified and the ped is in another vehicle then ped will get out the car and attempt to get in the correct car and then drive to the point. * If no vehicle is specified then the ped will attempt to get in any nearby vehicle and drive to the point. * If no vehicle is specified and the ped is already in a car then the ped will drive the car to the point. If a ped tries and fails to get in a car
```
