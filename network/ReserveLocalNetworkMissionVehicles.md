---
ns: NETWORK
aliases: ["0x42613035157e4208"]
---
## RESERVE_LOCAL_NETWORK_MISSION_VEHICLES

```c
// 0x42613035157E4208
void RESERVE_LOCAL_NETWORK_MISSION_VEHICLES(int NumVehiclesToReserve);
```

```
Reserves space in the population pool for the given number of vehicles. ** This space will only be reserved locally, and will be added to the reservation in RESERVE_NETWORK_MISSION_VEHICLES. Use this if you don't want the reservations affecting the populations of nearby players who are not running the script **
```
