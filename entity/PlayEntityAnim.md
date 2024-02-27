---
ns: ENTITY
aliases: ["0x7fb218262b810701"]
---
## PLAY_ENTITY_ANIM

```c
// 0x7FB218262B810701
bool PLAY_ENTITY_ANIM(string AnimName, string AnimDictName, float BlendDelta, bool Loop, bool HoldLastFrame, bool DriveToPose, float StartPhase, int AnimFlags);
```

Play an entity anim.


## Parameters
* **AnimName**: 
* **AnimDictName**: 
* **BlendDelta**: 
* **Loop**: 
* **HoldLastFrame**: 
* **DriveToPose**: enable drive-to-pose for the animation (object must be setup with articulation for this to work) (Default value: `False`)
* **StartPhase**: (Default value: `0`)
* **AnimFlags**: (Default value: `0`)
