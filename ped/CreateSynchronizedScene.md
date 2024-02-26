---
ns: PED
aliases: ["0x8c18e0f9080add73"]
---
## CREATE_SYNCHRONIZED_SCENE

```c
// 0x8C18E0F9080ADD73
int CREATE_SYNCHRONIZED_SCENE(Vector3 sceneOrientation, int RotOrder);
```

Creates a new scene origin for playing back synchronized anims across multiple entities. Should be called immediately before starting the first anim on a scene.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


Creates a common scene origin which can be used to playback synchronised animations across multiple peds and objects


## Parameters
* **sceneOrientation**: The orientation of the scene root in world coordinates
* **RotOrder**: 
