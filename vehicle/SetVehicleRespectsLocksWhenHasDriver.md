---
ns: VEHICLE
aliases: ["0x2311dd7159f00582"]
---
## SET_VEHICLE_RESPECTS_LOCKS_WHEN_HAS_DRIVER

```c
// 0x2311DD7159F00582
void SET_VEHICLE_RESPECTS_LOCKS_WHEN_HAS_DRIVER(Vehicle vehicle, bool RespectLocks);
```

Vehicle locks are ignored for vehicles with drivers by default - setting this flag ensures locks are always checked

