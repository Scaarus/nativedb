---
ns: CAMERA
aliases: ["0xa2746eeae3e577cd"]
---
## ANIMATED_SHAKE_CAM

```c
// 0xA2746EEAE3E577CD
void ANIMATED_SHAKE_CAM(Camera camera, string AnimDictionary, string AnimClipName, string ShakeName, float fAmplitudeScalar);
```

Set a camera animation to play on scripted camera.


## Parameters
* **camera**: 
* **AnimDictionary**: The name of the animation dictionary containing the animation to be rendered as a shake.
* **AnimClipName**: The name of the animation to be rendered as a shake.
* **ShakeName**: Controls how shake ramps updown at startend [OPTIONAL parameter]
* **fAmplitudeScalar**: Can be used to increase or decrease the amplitude of the shake effect. (Default value: `1`)
