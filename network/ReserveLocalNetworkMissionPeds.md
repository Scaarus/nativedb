---
ns: NETWORK
aliases: ["0x2c8df5d129595281"]
---
## RESERVE_LOCAL_NETWORK_MISSION_PEDS

```c
// 0x2C8DF5D129595281
void RESERVE_LOCAL_NETWORK_MISSION_PEDS(int NumPedsToReserve);
```

```
Reserves space in the population pool for the given number of peds. ** This space will only be reserved locally, and will be added to the reservation in RESERVE_NETWORK_MISSION_PEDS. Use this if you don't want the reservations affecting the populations of nearby players who are not running the script **
```
