---
ns: CAMERA
aliases: ["0xfd3151cd37ea2245"]
---
## SET_GAMEPLAY_CAM_ENTITY_TO_LIMIT_FOCUS_OVER_BOUNDING_SPHERE_THIS_UPDATE

```c
// 0xFD3151CD37EA2245
void SET_GAMEPLAY_CAM_ENTITY_TO_LIMIT_FOCUS_OVER_BOUNDING_SPHERE_THIS_UPDATE(Entity entity);
```

```
The gameplay camera will prevent the adaptive depth of field focus distance from going beyond the bounding sphere of this entity, so long as the camera (the centre of the frame) is pointing at it, on this update (only.) This setting automatically resets for safety.
```
