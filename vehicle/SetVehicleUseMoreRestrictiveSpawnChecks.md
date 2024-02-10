---
ns: VEHICLE
aliases: ["0x88bc673ca9e0ae99"]
---
## SET_VEHICLE_USE_MORE_RESTRICTIVE_SPAWN_CHECKS

```c
// 0x88BC673CA9E0AE99
void SET_VEHICLE_USE_MORE_RESTRICTIVE_SPAWN_CHECKS(Vehicle vehicle, bool UseRestrictiveCheck);
```

```
This is used for cases where a car might be driving on the wrong side of the road or avoiding cars at a distance away from the player where other cars might be trying to spawn. It's somewhat expensive so we don't do it for everybody NOTE: This is a reset flag and needs to be called each frame

Passing TRUE to this command will do some extra trajectory checks with this vehicle to prevent other vehicles from spawning in its way
```
