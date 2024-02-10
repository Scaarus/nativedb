---
ns: VEHICLE
aliases: ["0x44cd1f493db2a0a6"]
---
## SET_VEHICLE_WEAPON_RESTRICTED_AMMO

```c
// 0x44CD1F493DB2A0A6
void SET_VEHICLE_WEAPON_RESTRICTED_AMMO(int VehicleWeaponIndex, int AmmoCount);
```

Sets a limited number of ammo for a particular vehicle weapon index on a script vehicle.


## Parameters
* **VehicleWeaponIndex**: Between 0 and 3, corresponds to each weapon slot in the vehicle's handling.meta.
* **AmmoCount**: When set positive, will count down with every fire and prevent firing at 0. Set -1 to disable restricted ammo.
