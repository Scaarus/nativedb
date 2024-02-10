---
ns: CAMERA
aliases: ["0xe32efe9ab4a9aa0c"]
---
## PLAY_SYNCHRONIZED_CAM_ANIM

```c
// 0xE32EFE9AB4A9AA0C
bool PLAY_SYNCHRONIZED_CAM_ANIM(Camera camera, int SceneId, string AnimName, string AnimDictName);
```

```
Play a camera animation on the specified camera, attached to the specified synchronized scene. Note that the animation must already be loaded prior to calling this command.
```

## Parameters
* **camera**: 
* **SceneId**: 
* **AnimName**: The name of the animation to be played on the camera.
* **AnimDictName**: The name of the animation dictionary containing the animation to be played on the camera.
