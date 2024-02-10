---
ns: VEHICLE
aliases: ["0xf4b2ed59deb5d774"]
---
## SET_VEHICLE_BOMB_AMMO

```c
// 0xF4B2ED59DEB5D774
void SET_VEHICLE_BOMB_AMMO(int AmmoCount);
```

Sets the current bomb ammo count for a script vehicle. Unlike restricted vehicle ammo (which is code fired), this is script-fired and manually decremented, and only stored in vehicle code for network sync purposes.


## Parameters
* **AmmoCount**: Must be positive (0 or greater).
