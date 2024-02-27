---
ns: ENTITY
aliases: ["0x54736aa40e271165"]
---
## IS_ENTITY_IN_AREA

```c
// 0x54736AA40E271165
bool IS_ENTITY_IN_AREA(Entity entity, Vector3 Position1, Vector3 Position2, bool HighlightArea, bool Do3dCheck, int TM_MODE);
```

Checks if a ped is in the axis aligned area defined by the two coords. If the entity is a ped in a vehicle, then the coords of the vehicle are used in the check.

## TM_MODE Values:
| Value | Name |
| --- | --- |
| 0 | Any (Any Mode Of Transport Bike, Car Plane, On Foot Etc) |
| 1 | On Foot (The Ped Is On Foot) |
| 2 | In Vehicle (The Ped Is In A Vehicle Not On Foot) |


PARAM NOTES :


## Parameters
* **entity**: 
* **Position1**: 
* **Position2**: 
* **HighlightArea**: (Default value: `False`)
* **Do3dCheck**: (Default value: `True`)
* **TM_MODE**: (Default value: `Tm_Any`)
