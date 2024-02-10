---
ns: VEHICLE
aliases: ["0x02398b627547189c"]
---
## SET_VEHICLE_HAS_BEEN_DRIVEN_FLAG

```c
// 0x02398B627547189C
void SET_VEHICLE_HAS_BEEN_DRIVEN_FLAG(Vehicle vehicle, bool State);
```

```
Sets the vehicle flag which records whether this vehicle has been driven. Scriptedcargen vehicles which have not yet been driven are not cleaned up so aggressively as those which have been driven & then abandoned.
```
