---
ns: ENTITY
aliases: ["0x06843da7060a026b"]
---
## SET_ENTITY_COORDS

```c
// 0x06843DA7060A026B
void SET_ENTITY_COORDS(Entity entity, Vector3 NewPosition, bool DoDeadCheck, bool KeepTasks, bool KeepIK, bool DoWarp);
```

Sets the entity's coords (peds add an -1m offset from the peds origin).

If you want to set the coords of a ped in a vehicle, use SET_PED_COORDS_KEEP_VEHICLE. If you set the z component of VecNewCoors to INVALID_WORLD_Z this command to automatically find the ground z for your entity if there is collision.


## Parameters
* **entity**: 
* **NewPosition**: 
* **DoDeadCheck**: If false then the command will not assert if the entity has not been checked for being dead
* **KeepTasks**: only applied to peds. If true, the tasks on the ped are not removed when he is teleported.
* **KeepIK**: only applied to peds. If true, the IK on the ped is not reset when he is teleported.
* **DoWarp**: Calling with the non-default value of FALSE implies that the object has continuous motion and should not clear contacts nor space for itself.
