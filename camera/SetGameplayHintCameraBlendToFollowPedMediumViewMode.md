---
ns: CAMERA
aliases: ["0xe3433eadaaf7ee40"]
---
## SET_GAMEPLAY_HINT_CAMERA_BLEND_TO_FOLLOW_PED_MEDIUM_VIEW_MODE

```c
// 0xE3433EADAAF7EE40
void SET_GAMEPLAY_HINT_CAMERA_BLEND_TO_FOLLOW_PED_MEDIUM_VIEW_MODE(bool State);
```

```
Allows an active follow-ped camera to be blended into the medium third-person view mode based upon the hint blend level, which should ensure consistent hint framing.

Call at the start of the hint to avoid pops.
```
