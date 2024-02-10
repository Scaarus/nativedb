---
ns: VEHICLE
aliases: ["0xc45d23baf168aab8"]
---
## GET_VEHICLE_ENGINE_HEALTH

```c
// 0xC45D23BAF168AAB8
float GET_VEHICLE_ENGINE_HEALTH(Vehicle vehicle);
```

```
Get engine health for a vehicle.

1000.0 = full, 0.0 = go on fire, -1000.0 = burnt out While on fire, burning engine "may" set the petrol tank on fire as well, but there's only a chance of this. While on fire engine health will drop until it reaches -1000.0 Engine health < 0.0 means engine won't work.
```
