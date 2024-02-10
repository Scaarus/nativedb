---
ns: VEHICLE
aliases: ["0x10655fab9915623d"]
---
## SET_VEHICLE_IMPATIENCE_TIMER

```c
// 0x10655FAB9915623D
void SET_VEHICLE_IMPATIENCE_TIMER(Vehicle vehicle, int HandlingOverrideMs);
```

```
Overrides the amount of time a vehicle will wait before thinking it's stuck on something.

Pass in -1 to reset to the default value (vehicle-dependent)
```
