---
ns: CAMERA
aliases: ["0xc92717ef615b6704"]
---
## SET_GAMEPLAY_HINT_CAMERA_RELATIVE_VERTICAL_OFFSET

```c
// 0xC92717EF615B6704
void SET_GAMEPLAY_HINT_CAMERA_RELATIVE_VERTICAL_OFFSET(float VerticalOffset);
```

Sets an vertical offset relative attach parent in metres.

Call at the start of the hint to avoid pops. This will cause the camera to pull back to frame the player correctly, May need to use in conjunction with the [SET_GAMEPLAY_HINT_FOLLOW_DISTANCE_SCALAR](#_0xF8BDBF3D573049A1)

