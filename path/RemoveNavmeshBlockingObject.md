---
ns: PATH
aliases: ["0x46399a7895957c0e"]
---
## REMOVE_NAVMESH_BLOCKING_OBJECT

```c
// 0x46399A7895957C0E
void REMOVE_NAVMESH_BLOCKING_OBJECT();
```

All blocking objects added with the default "bPermanent=FALSE" will be automatically removed when the script which added them teminates - there is no need to manually remove these objects in this case.
The "iObjectId" must be a valid index as returned by "ADD_NAVMESH_BLOCKING_OBJECT"

This command removes a blocking object which was previously added via "ADD_NAVMESH_BLOCKING_OBJECT"

