---
ns: ENTITY
aliases: ["0x3fef770d40960d5a"]
---
## GET_ENTITY_COORDS

```c
// 0x3FEF770D40960D5A
Vector3 GET_ENTITY_COORDS(Entity entity, bool DoDeadCheck);
```

Gets the co-ordinates of the entity. If a ped, this is at the root bone, and if the ped is in a vehicle then it is the coordinates of the vehicle which are returned.


## Parameters
* **entity**: 
* **DoDeadCheck**: If false then the command will not assert if the entity has not been checked for being dead
