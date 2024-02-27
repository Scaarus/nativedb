---
ns: CAMERA
aliases: ["0x9a2d0fb2e7852392"]
---
## PLAY_CAM_ANIM

```c
// 0x9A2D0FB2E7852392
bool PLAY_CAM_ANIM(Camera camera, string AnimName, string AnimDictName, Vector3 vOriginPosition, Vector3 vOriginRotation, int AnimFlags, int RotOrder);
```

Play a camera animation on the specified camera. Note that the animation must already be loaded prior to calling this command.

## AnimFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Looping |


## RotOrder Values:
| Value | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |


## Parameters
* **camera**: 
* **AnimName**: The name of the animation to be played on the camera.
* **AnimDictName**: The name of the animation dictionary containing the animation to be played on the camera.
* **vOriginPosition**: The position of the origin in world coordinates to playback the anim from. Any local scene originoffset specified in the animation clip will be applied in addition to this.
* **vOriginRotation**: The rotation of the origin in degrees (<< pitch, roll, heading >>) to playback the anim from. Any local scene originoffset specified in the animation clip will be applied in addition to this.
* **AnimFlags**: The animation flags to be used for playback. (Default value: `Default`)
* **RotOrder**: The rotation order to be used when composing a matrix from the Euler angles specified in vOriginRotation. Defaults to YXZ order. (Default value: `Yxz`)
