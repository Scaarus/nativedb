---
ns: ENTITY
aliases: ["0xc77720a12fe14a86"]
---
## PLAY_SYNCHRONIZED_ENTITY_ANIM

```c
// 0xC77720A12FE14A86
bool PLAY_SYNCHRONIZED_ENTITY_ANIM(int SceneId, string AnimName, string AnimDictName, float BlendInDelta, float BlendOutDelta, int Flags, float MoverBlendInDelta);
```

Play a synchronized anim on the entity using the synchronized scene provided. more info...

Use this to add an entity with a specifically authored anim to a synchronized scene created with CREATE_SYNCHRONIZED_SCENE Note: as part of this process the entity's collision will be deactivated. To turn it back on again, use [`SET_ENTITY_COLLISION`](#_0x1A9205C1B9EE827F) or pass a true value to the ActivateCollision parameter of STOP_SYNCHRONISED_ENTITY_ANIM.


## Parameters
* **SceneId**: 
* **AnimName**: The name of the paired anim to play. AnimDictName The name of the anim dictionary the anim is in
* **AnimDictName**: 
* **BlendInDelta**: the rate at which the task will blend in The blend in duration is 1.0 BlendInDelta e.g. 1.0 NORMAL_BLEND_IN -> 1.0 8.0 = 0.125 seconds
* **BlendOutDelta**: the rate at which the task will blend out The blend out duration is -1.0 BlendOutDelta e.g. -1.0 NORMAL_BLEND_OUT -> -1.0 -8.0 = 0.125 seconds (Default value: `8`)
* **Flags**: The synced scene flags to use (see commands_task. (Default value: `0`)
* **MoverBlendInDelta**: the rate at which the mover blends in to the scene. This can be usefull for seamless entry onto a synced scene. (e.g. (Default value: `1000`)
