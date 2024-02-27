---
ns: MISC
aliases: ["0xe54e209c35ffa18d"]
---
## IS_POINT_OBSCURED_BY_A_MISSION_ENTITY

```c
// 0xE54E209C35FFA18D
bool IS_POINT_OBSCURED_BY_A_MISSION_ENTITY(Vector3 CentrePosition, Vector3 LocateDimensions, Entity entity);
```

Returns TRUE if any mission-created vehicles, peds or objects are in the defined area.

ExludedEntityIndex (Optional) allows for an entity that is ignored by the area check


## Parameters
* **CentrePosition**: 
* **LocateDimensions**: 
* **entity**: (Default value: `Null`)
