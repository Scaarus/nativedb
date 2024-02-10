---
ns: VEHICLE
aliases: ["0xea12bd130d7569a1"]
---
## GET_VEHICLE_BOMB_AMMO

```c
// 0xEA12BD130D7569A1
int GET_VEHICLE_BOMB_AMMO();
```

Gets the current bomb ammo count for a script vehicle. Unlike restricted vehicle ammo (which is code fired), this is script-fired and manually decremented, and only stored in vehicle code for network sync purposes.

