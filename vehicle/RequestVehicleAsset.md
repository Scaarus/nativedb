---
ns: VEHICLE
aliases: ["0x81a15811460fab3a"]
---
## REQUEST_VEHICLE_ASSET

```c
// 0x81A15811460FAB3A
void REQUEST_VEHICLE_ASSET(Hash modelHash, int iVehicleRequestFlags);
```

Requests the peds enter/exit/in vehicle animationsfor this vehicle.

iVehicleRequestFlags can be from the enum VEHICLE_RESOURCE_FLAGS, then can be combined together using "|"

Used to prevent delays for missions peds getting out/in to vehicles waiting for anims to load


## Parameters
* **modelHash**: 
* **iVehicleRequestFlags**: (Default value: `Vrf_Request_Basic_Anims`)
