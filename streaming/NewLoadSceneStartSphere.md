---
ns: STREAMING
aliases: ["0xaccfb4acf53551b0"]
---
## NEW_LOAD_SCENE_START_SPHERE

```c
// 0xACCFB4ACF53551B0
bool NEW_LOAD_SCENE_START_SPHERE(Vector3 pos, float radius, int controlFlags);
```

asynchronously load a location (could be inside an interior, or not). returns true if load scene has started successfully, false otherwise.

## controlFlags Values:
| Value | Name |
| --- | --- |
| 1 | Require Collision |
| 2 | Longswitch Cutscene |
| 4 | Interior And Exterior |


position, direction of camera, range (e.g. 20m)

starts a new spherical load scene, which is interior-aware and uses a streaming volume. this cannot be used during a player switch.

