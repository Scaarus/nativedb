---
ns: TASK
aliases: ["0x15c86013127ce63f"]
---
## TASK_BOAT_MISSION

```c
// 0x15C86013127CE63F
void TASK_BOAT_MISSION(Vehicle vehicle, Vehicle vehicle, Ped ped, Vector3 Position, int Mission, float CruiseSpeed, int mode, float TargetReachedDist, int BoatFlags);
```

Gives the boat a mission.

## Mission Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Cruise 1 |
| 2 | Ram 2 |
| 3 | Block 3 |
| 4 | Goto 4 |
| 5 | Stop 5 |
| 6 | Attack 6 |
| 7 | Follow 7 |
| 8 | Flee 8 |
| 9 | Circle 9 |
| 10 | Escort Left 10 |
| 11 | Escort Right 11 |
| 12 | Escort Rear 12 |
| 13 | Escort Front 13 |
| 14 | Goto Racing 14 |
| 15 | Follow Recording 15 |
| 16 | Police Behaviour 16 |
| 17 | Park Perpendicular 17 |
| 18 | Park Parallel 18 |
| 19 | Land 19 |
| 20 | Land And Wait 20 |
| 21 | Crash 21 |
| 22 | Pull Over 22 |
| 23 | Protect 23 |


## mode Values:
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


## BoatFlags Values:
| Value | Name |
| --- | --- |
| 1 | Stopatend |
| 2 | Stopatshore |
| 4 | Avoidshore |
| 7 | Defaultsettings |
| 8 | Preferforward |
| 16 | Neverstop |
| 32 | Nevernavmesh |
| 64 | Neverroute |
| 111 | Openoceansettings |
| 128 | Forcebeached |
| 256 | Usewanderroute |
| 512 | Usefleeroute |
| 1024 | Neverpause |
| 1071 | Boattaxisettings |


VEHICLE_INDEX VehicleIndex (The actual plane that will be flown) VEHICLE_INDEX TargetVehicleIndex (If a target vehicle needs to be specified it is done here) PED_INDEX TargetPedIndex (If a target ped needs to be specified it is done here) FLOAT TargetX, TargetY, TargetZ (specify targetcoordinates here in needed.) VEHICLE_MISSION Mission (Mission to be exectuted. ie MISSION_GOTO, MISSION_ATTACK, MISSION_FOLLOW) in commands_vehicle.sch X:\GTA\gta_rage_scripts\include\commands_vehicle.sch FLOAT CruiseSpeed (in ms) FLOAT TargetReachedDist (distance (in meters) at which plane thinks it's arrived.) ALSO used as the hover distance for MISSION_ATTACK and MISSION_CIRCLE INT BoatFlags

