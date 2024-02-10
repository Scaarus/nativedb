---
ns: ENTITY
aliases: ["0x239a3351ac1da385"]
---
## SET_ENTITY_COORDS_NO_OFFSET

```c
// 0x239A3351AC1DA385
void SET_ENTITY_COORDS_NO_OFFSET(Entity entity, Vector3 NewPosition, bool KeepTasks, bool KeepIK, bool DoWarp);
```

Sets the entity's coords without adding the offset.

If you set the z component of VecNewCoors to INVALID_WORLD_Z this command to automatically find the ground z for your entity if there is collision.


## Parameters
* **entity**: 
* **NewPosition**: 
* **KeepTasks**: only applied to peds. If true, the tasks on the ped are not removed when he is teleported.
* **KeepIK**: only applied to peds. If true, the IK on the ped is not reset when he is teleported.
* **DoWarp**: Calling with the non-default value of FALSE implies that the object has continuous motion and should not clear contacts nor space for itself.
