---
ns: VEHICLE
aliases: ["0x9bda23bf666f0855"]
---
## SET_VEHICLE_COUNTERMEASURE_AMMO

```c
// 0x9BDA23BF666F0855
void SET_VEHICLE_COUNTERMEASURE_AMMO(int AmmoCount);
```

Sets the current countermeasure ammo count for a script vehicle. Unlike restricted vehicle ammo (which is code fired), this is script-fired and manually decremented, and only stored in vehicle code for network sync purposes.


## Parameters
* **AmmoCount**: Must be positive (0 or greater).
