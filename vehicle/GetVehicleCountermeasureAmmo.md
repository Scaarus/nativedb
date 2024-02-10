---
ns: VEHICLE
aliases: ["0xf846aa63df56b804"]
---
## GET_VEHICLE_COUNTERMEASURE_AMMO

```c
// 0xF846AA63DF56B804
int GET_VEHICLE_COUNTERMEASURE_AMMO();
```

```
Gets the current countermeasure ammo count for a script vehicle. Unlike restricted vehicle ammo (which is code fired), this is script-fired and manually decremented, and only stored in vehicle code for network sync purposes.
```
