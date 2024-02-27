---
ns: PATH
aliases: ["0xfcd5c8e06e502f5a"]
---
## ADD_NAVMESH_BLOCKING_OBJECT

```c
// 0xFCD5C8E06E502F5A
int ADD_NAVMESH_BLOCKING_OBJECT(Vector3 vSizeXYZ, float fHeading, bool Permanent, int iFlags);
```

This command will assert if two objects are added at the same XYZ position, this is order to catch duplicates.

## Values for `iFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Wanderpath |
| 2 | Shortestpath |
| 4 | Fleepath |
| 7 | Allpaths |


vPosition : the center of the box vSizeXYZ : the width, depth & height of the box fHeading : the rotation of the object in bPermanent : if the object will last outside the lifetime of the callig script (always set to FALSE except in very special cases!) iFlags : a set of flags from the BLOCKING_OBJECT_FLAGS enumation; can be used to block certain types of pathfinding only. TIP : To help setting up blocking objects in the game, use the RAG

This function adds a blocking obstacle in the navmesh, which will prevent peds from pathfinding through it.


## Parameters
* **vSizeXYZ**: 
* **fHeading**: 
* **Permanent**: (Default value: `False`)
* **iFlags**: (Default value: `Allpaths`)
