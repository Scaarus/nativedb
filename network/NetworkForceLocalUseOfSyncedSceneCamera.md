---
ns: NETWORK
aliases: ["0xc9b43a33d09cada7"]
---
## NETWORK_FORCE_LOCAL_USE_OF_SYNCED_SCENE_CAMERA

```c
// 0xC9B43A33D09CADA7
void NETWORK_FORCE_LOCAL_USE_OF_SYNCED_SCENE_CAMERA(int NetworkSceneID);
```

Forces the local use of any camera attached to the synchronised scene to play, even if the local player ped has not been added to the scene. If this is not called the camera will only animate for scenes with the player ped involved. This only affects the local player as this data is not synced

