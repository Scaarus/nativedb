---
ns: ENTITY
aliases: ["0xafbd61cc738d9eb9"]
---
## GET_ENTITY_ROTATION

```c
// 0xAFBD61CC738D9EB9
Vector3 GET_ENTITY_ROTATION(Entity entity, int RotOrder);
```

Gets the rotation of an entity.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


The angles are between -180 and 180 not between 0 to 360


## Parameters
* **entity**: 
* **RotOrder**: (Default value: `Yxz`)
