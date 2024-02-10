---
ns: STREAMING
aliases: ["0xef39ee20c537e98c"]
---
## SET_SRL_POST_CUTSCENE_CAMERA

```c
// 0xEF39EE20C537E98C
void SET_SRL_POST_CUTSCENE_CAMERA(Vector3 camPos, Vector3 camDir);
```

```
Call this at any time before or during a cutscene (but ideally at least 5 seconds before it ends) to indicate where the camera will be after the cutscene is over. The streaming system will make sure that scene is in memory before the cutscene switches back to normal gameplay.

camPos indicates the camera position, camDir is the direction it is looking at.
```
