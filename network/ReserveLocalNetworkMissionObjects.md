---
ns: NETWORK
aliases: ["0x797f9c5e661d920e"]
---
## RESERVE_LOCAL_NETWORK_MISSION_OBJECTS

```c
// 0x797F9C5E661D920E
void RESERVE_LOCAL_NETWORK_MISSION_OBJECTS(int NumObjectsToReserve);
```

Reserves space in the population pool for the given number of objects. ** This space will only be reserved locally, and will be added to the reservation in [RESERVE_NETWORK_MISSION_OBJECTS](#_0x4E5C93BD0C32FBF8). Use this if you don't want the reservations affecting the populations of nearby players who are not running the script **

