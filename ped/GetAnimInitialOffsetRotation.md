---
ns: PED
aliases: ["0x4b805e6046ee9e47"]
---
## GET_ANIM_INITIAL_OFFSET_ROTATION

```c
// 0x4B805E6046EE9E47
Vector3 GET_ANIM_INITIAL_OFFSET_ROTATION(string pAnimName, Vector3 scenePosition, Vector3 sceneOrientation, float phase, int RotOrder);
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


Used when playing multiple anims together using TASK_PLAY_ANIM. This function returns the rotational offset (pitch, roll and heading, in that order) that will be automatically applied when playing the specified anim using the anim flag AF_EXTRACT_INITIAL_OFFSET from the initial position and orientation specified


## Parameters
* **pAnimName**: 
* **scenePosition**: the position to be used with TASK_PLAY_ANIM_ADVANCED (in world coords)
* **sceneOrientation**: The orientation to be used with TASK_PLAY_ANIM_ADVANCED (<< pitch, roll, heading >>)
* **phase**: 
* **RotOrder**: 
