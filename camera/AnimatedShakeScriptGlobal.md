---
ns: CAMERA
aliases: ["0xc2eae3fb8cdbed31"]
---
## ANIMATED_SHAKE_SCRIPT_GLOBAL

```c
// 0xC2EAE3FB8CDBED31
void ANIMATED_SHAKE_SCRIPT_GLOBAL(string AnimDictionary, string AnimClipName, string ShakeName, float fAmplitudeScalar);
```

```
Apply an animated shake globally to the rendered result of all active scripted cameras.
```

## Parameters
* **AnimDictionary**: The name of the animation dictionary containing the animation to be rendered as a shake.
* **AnimClipName**: The name of the animation to be rendered as a shake.
* **ShakeName**: Controls how shake ramps updown at startend [OPTIONAL parameter]
* **fAmplitudeScalar**: Can be used to increase or decrease the amplitude of the shake effect.
