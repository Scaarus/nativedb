---
ns: PATH
aliases: ["0x0eaeb0db4b132399"]
---
## DOES_NAVMESH_BLOCKING_OBJECT_EXIST

```c
// 0x0EAEB0DB4B132399
bool DOES_NAVMESH_BLOCKING_OBJECT_EXIST();
```

```
Queries whether a navmesh blocking object with the specfied index exists This may be useful during mission shutdown, or SF skips, where the mission-cleanup code automatically removes all the objects which the script adds - but where the script itself may try to manually remove them. Wrapping REMOVE_NAVMESH_BLOCKING_OBJECT with a call to DOES_NAVMESH_BLOCKING_OBJECT_EXIST, will ensure there are no warnings about the script trying to remove an object which doesn't exist.
```
