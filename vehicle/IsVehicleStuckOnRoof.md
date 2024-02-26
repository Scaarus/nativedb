---
ns: VEHICLE
aliases: ["0xb497f06b288dcfdf"]
---
## IS_VEHICLE_STUCK_ON_ROOF

```c
// 0xB497F06B288DCFDF
bool IS_VEHICLE_STUCK_ON_ROOF(Vehicle vehicle);
```

Checks that a vehicle is stuck on its roof.

If the deatharrest code is switched off, it is still possible to check for a particular car being stuck on its roof. Before using this command, you must have called [ADD_VEHICLE_UPSIDEDOWN_CHECK](#_0xB72E26D81006005B) for CarID.

