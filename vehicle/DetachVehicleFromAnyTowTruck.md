---
ns: VEHICLE
aliases: ["0xd0e9ce05a1e68cd8"]
---
## DETACH_VEHICLE_FROM_ANY_TOW_TRUCK

```c
// 0xD0E9CE05A1E68CD8
bool DETACH_VEHICLE_FROM_ANY_TOW_TRUCK(Vehicle vehicle);
```

Returns true if it has been detached from a tow truck

Detaches specified vehicle from any tow truck it might be attached through, loops through all vehicles so could be expensive

