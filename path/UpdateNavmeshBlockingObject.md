---
ns: PATH
aliases: ["0x109e99373f290687"]
---
## UPDATE_NAVMESH_BLOCKING_OBJECT

```c
// 0x109E99373F290687
void UPDATE_NAVMESH_BLOCKING_OBJECT(Vector3 vPosition, Vector3 vSizeXYZ, float fHeading, int iFlags);
```

## Values for `iFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Wanderpath |
| 2 | Shortestpath |
| 4 | Fleepath |
| 7 | Allpaths |


The "iObjectId" must be a valid index as returned by "[`ADD_NAVMESH_BLOCKING_OBJECT`](#_0xFCD5C8E06E502F5A)"

This command updates the position, size & orientation of a navmesh blocking object


## Parameters
* **vPosition**: 
* **vSizeXYZ**: 
* **fHeading**: 
* **iFlags**: (Default value: `Allpaths`)
