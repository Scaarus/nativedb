---
ns: ENTITY
aliases: ["0x295d82a8559f9150"]
---
## SET_ENTITY_MOTION_BLUR

```c
// 0x295D82A8559F9150
void SET_ENTITY_MOTION_BLUR(Entity entity, bool EnableMotionBlur);
```

Passing FALSE will keep the entity from being affected by the motion blur effect The effect of this call is permanent, so it is up to the user to restore any previous state

Toggles motion blur on an entity

