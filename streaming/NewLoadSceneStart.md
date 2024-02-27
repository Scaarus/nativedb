---
ns: STREAMING
aliases: ["0x212a8d0d2babfac2"]
---
## NEW_LOAD_SCENE_START

```c
// 0x212A8D0D2BABFAC2
bool NEW_LOAD_SCENE_START(Vector3 pos, Vector3 dir, float farClip, int controlFlags);
```

asynchronously load a location (could be inside an interior, or not). returns true if load scene has started successfully, false otherwise.

## controlFlags Values:
| Value | Name |
| --- | --- |
| 1 | Require Collision |
| 2 | Longswitch Cutscene |
| 4 | Interior And Exterior |


position, direction of camera, range (e.g. 20m)

starts a new frustum load scene, which is interior-aware and uses a streaming volume


## Parameters
* **pos**: 
* **dir**: 
* **farClip**: 
* **controlFlags**: (Default value: `0`)
