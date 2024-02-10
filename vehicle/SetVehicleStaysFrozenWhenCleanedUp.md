---
ns: VEHICLE
aliases: ["0x1cf38d529d7441d9"]
---
## SET_VEHICLE_STAYS_FROZEN_WHEN_CLEANED_UP

```c
// 0x1CF38D529D7441D9
void SET_VEHICLE_STAYS_FROZEN_WHEN_CLEANED_UP(Vehicle vehicle, bool StaysFrozen);
```

Call this with TRUE if you've already called FREEZE_ENTITY_POSITION(TRUE) for this vehicle and you want it to stay frozen even after it's marked as no longer needed


## Parameters
* **vehicle**: 
* **StaysFrozen**: FALSE is the default behaviour
