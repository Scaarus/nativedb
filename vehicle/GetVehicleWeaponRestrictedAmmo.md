---
ns: VEHICLE
aliases: ["0x8181ce2f25cb9bb7"]
---
## GET_VEHICLE_WEAPON_RESTRICTED_AMMO

```c
// 0x8181CE2F25CB9BB7
int GET_VEHICLE_WEAPON_RESTRICTED_AMMO(int VehicleWeaponIndex);
```

Gets the current restricted ammo count for a particular vehicle weapon index on a script vehicle.


## Parameters
* **VehicleWeaponIndex**: Between 0 and 3, corresponds to each weapon slot in the vehicle's handling.meta.
