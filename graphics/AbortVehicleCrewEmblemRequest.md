---
ns: GRAPHICS
aliases: ["0x82acc484ffa3b05f"]
---
## ABORT_VEHICLE_CREW_EMBLEM_REQUEST

```c
// 0x82ACC484FFA3B05F
bool ABORT_VEHICLE_CREW_EMBLEM_REQUEST(Vehicle vehicle);
```

Aborts crew emblem requests from a vehicle (the requests must be stuck in a "requesting badge" state) If the abort is successful this command will return true - otherwise it'll return false

