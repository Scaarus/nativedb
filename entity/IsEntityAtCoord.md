---
ns: ENTITY
aliases: ["0x20b60995556d004f"]
---
## IS_ENTITY_AT_COORD

```c
// 0x20B60995556D004F
bool IS_ENTITY_AT_COORD(Entity entity, Vector3 Position, Vector3 LocDimensions, bool HighlightArea, bool Do3dCheck, int TM_MODE);
```

Checks if the entity's root is located in the given area defined by a centre point and a locate size. If the entity is a ped in a vehicle, then the coords of the vehicle are used in the check.

## TM_MODE Values:
| Value | Name |
| --- | --- |
| 0 | Any (Any Mode Of Transport Bike, Car Plane, On Foot Etc) |
| 1 | On Foot (The Ped Is On Foot) |
| 2 | In Vehicle (The Ped Is In A Vehicle Not On Foot) |

