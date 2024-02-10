---
ns: CAMERA
aliases: ["0xe111a7c0d200cbc5"]
---
## SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE_BLEND_LEVEL

```c
// 0xE111A7C0D200CBC5
void SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE_BLEND_LEVEL(Camera camera, float blendLevel);
```

```
Controls the blend between the custom focus distance specified by SET_CAM_DOF_OVERRIDDEN_FOCUS_DISTANCE and the focus distance that is computed based upon the depth of the scene.

The valid range of 'blendLevel' is 0.0 to 1.0.
```
