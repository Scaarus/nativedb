---
ns: ENTITY
aliases: ["0x751b70c3d034e187"]
---
## IS_ENTITY_AT_ENTITY

```c
// 0x751B70C3D034E187
bool IS_ENTITY_AT_ENTITY(Entity entity, Entity entity, Vector3 LocDimensions, bool HighlightArea, bool Do3dCheck, int TM_MODE);
```

Checks if the entity is in the area around a vehicle. If the entity is a ped in a vehicle, then the coords of the vehicle are used in the check.

## TM_MODE Values:
| Value | Name |
| --- | --- |
| 0 | Any Any Mode Of Transport Bike, Car Plane, On Foot Etc |
| 1 | On Foot The Ped Is On Foot |
| 2 | In Vehicle The Ped Is In A Vehicle Not On Foot |

