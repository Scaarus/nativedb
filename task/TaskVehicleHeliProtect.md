---
ns: TASK
aliases: ["0x1e09c32048fefd1c"]
---
## TASK_VEHICLE_HELI_PROTECT

```c
// 0x1E09C32048FEFD1C
void TASK_VEHICLE_HELI_PROTECT(Ped ped, Vehicle vehicle, Entity entity, float CruiseSpeed, int mode, float CustomOffset, int MinHeightAboveTerrain, int HeliFlags);
```

Identical to TASK_VEHICLE_MISSION with MISSION_PROTECT mission,

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

