---
ns: VEHICLE
aliases: ["0x70db57649fa8d0d8"]
---
## SET_VEHICLE_PETROL_TANK_HEALTH

```c
// 0x70DB57649FA8D0D8
void SET_VEHICLE_PETROL_TANK_HEALTH(Vehicle vehicle, float health);
```

Set petrol tank health for a vehicle.

1000.0 = full 0.0 = go on fire -1000.0 = burnt out

Petrol tank "will" explode when health reaches -1000.0 Petrol tank health will drop if on fire until it explodes

