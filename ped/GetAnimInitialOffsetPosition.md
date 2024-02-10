---
ns: PED
aliases: ["0xbe22b26dd764c040"]
---
## GET_ANIM_INITIAL_OFFSET_POSITION

```c
// 0xBE22B26DD764C040
Vector3 GET_ANIM_INITIAL_OFFSET_POSITION(string pAnimName, Vector3 scenePosition, Vector3 sceneOrientation, float phase, int RotOrder);
```

Gets the authored initial offset included by the animator, if any.

## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |


Used when playing multiple anims together using TASK_PLAY_ANIM. This function returns the position offset that will be automatically applied when playing the specified anim using the anim flag AF_EXTRACT_INITIAL_OFFSET from the initial position and orientation specified


## Parameters
* **pAnimName**: 
* **scenePosition**: the position to be used with TASK_PLAY_ANIM_ADVANCED (in world coords)
* **sceneOrientation**: The orientation to be used with TASK_PLAY_ANIM_ADVANCED (<< pitch, roll, heading >>)
* **phase**: 
* **RotOrder**: 
