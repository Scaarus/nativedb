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

