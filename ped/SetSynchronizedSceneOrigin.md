---
ns: PED
aliases: ["0x6acf6b7225801cd7"]
---
## SET_SYNCHRONIZED_SCENE_ORIGIN

```c
// 0x6ACF6B7225801CD7
void SET_SYNCHRONIZED_SCENE_ORIGIN(Vector3 scenePosition, Vector3 sceneOrientation, int RotOrder);
```

Changes the root position and orientation of an existing synchronized scene.

## Values for `RotOrder`:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


Use this command to change a synchronised scene's origin after it has been created


## Parameters
* **scenePosition**: the position of the scene root in world coordinates
* **sceneOrientation**: The orientation of the scene root in world coordinates
* **RotOrder**: (Default value: `Yxz`)
