---
ns: VEHICLE
aliases: ["0xb8ef61207c2393a9"]
---
## GET_VEHICLE_HEALTH_PERCENTAGE

```c
// 0xB8EF61207C2393A9
float GET_VEHICLE_HEALTH_PERCENTAGE(Vehicle vehicle, float maxEngineHealth, float maxPetrolTankHealth, float maxHealth, float maxMainRotorHealth, float maxRearRotorHealth, float maxTailBoomHealth);
```

Calculates the vehicle health as a percentage taking into account body health, engine health and petrol tank health and ensures the health is 0% when the vehicle is undriveable.

