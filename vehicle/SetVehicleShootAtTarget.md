---
ns: VEHICLE
aliases: ["0x74cd9a9327a282ea"]
---
## SET_VEHICLE_SHOOT_AT_TARGET

```c
// 0x74CD9A9327A282EA
void SET_VEHICLE_SHOOT_AT_TARGET(Ped ped, Entity entity, Vector3 vecTargetPosition);
```

Fire the ped's current vehicle weapon. It will fire the bullets or rockets in the direction of vehicle is facing if the target entity is NULL and target location is <<0.0, 0.0, 0.0>>.


## Parameters
* **ped**: 
* **entity**: 
* **vecTargetPosition**: fire at this location if it's not <<0.0, 0.0, 0.0>> and the target entity is NULL. Ignore this if the target entity is not NULL.
