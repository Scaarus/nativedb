---
ns: ENTITY
aliases: ["0x51210ced3da1c78a"]
---
## IS_ENTITY_IN_ANGLED_AREA

```c
// 0x51210CED3DA1C78A
bool IS_ENTITY_IN_ANGLED_AREA(Entity entity, Vector3 Position1, Vector3 Position2, float AreaWidth, bool HighlightArea, bool Do3dCheck, int TM_MODE);
```

Checks if a ped is in non axis aligned area, defined by coords of a face and distance between faces. If the entity is a ped in a vehicle, then the coords of the vehicle are used in the check.

## TM_MODE Values:
| Value | Name |
| --- | --- |
| 0 | Any Any Mode Of Transport Bike, Car Plane, On Foot Etc |
| 1 | On Foot The Ped Is On Foot |
| 2 | In Vehicle The Ped Is In A Vehicle Not On Foot |


VecCoors1 and VecCoors2 define the midpoints of two parallel sides and AreaWidth is the width of these sides.

