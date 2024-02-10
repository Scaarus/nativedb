---
ns: ENTITY
aliases: ["0xb9c54555ed30fbc4"]
---
## PLAY_SYNCHRONIZED_MAP_ENTITY_ANIM

```c
// 0xB9C54555ED30FBC4
bool PLAY_SYNCHRONIZED_MAP_ENTITY_ANIM(float Radius, Hash modelHash, int SceneId, string AnimName, string AnimDictName, float BlendDelta, float BlendOutDelta, int Flags, float MoverBlendInDelta);
```

Play a synchronized anim on the map entity using the synchronized scene provided. more info...

Use this to add an entity with a specifically authored anim to a synchronized scene created with CREATE_SYNCHRONIZED_SCENE Note: as part of this process the entity's collision will be deactivated. To turn it back on again, use SET_ENTITY_COLLISION or pass a true value to the ActivateCollision parameter of STOP_SYNCHRONISED_ENTITY_ANIM.


## Parameters
* **Radius**: 
* **modelHash**: 
* **SceneId**: 
* **AnimName**: The name of the paired anim to play. AnimDictName The name of the anim dictionary the anim is in
* **AnimDictName**: 
* **BlendDelta**: 
* **BlendOutDelta**: the rate at which the task will blend out The blend out duration is -1.0 BlendOutDelta e.g. -1.0 NORMAL_BLEND_OUT -> -1.0 -8.0 = 0.125 seconds
* **Flags**: The synced scene flags to use (see commands_task.
* **MoverBlendInDelta**: the rate at which the mover blends in to the scene. This can be usefull for seamless entry onto a synced scene. (e.g.
