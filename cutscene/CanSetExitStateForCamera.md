---
ns: CUTSCENE
aliases: ["0xb2cbcd0930dfb420"]
---
## CAN_SET_EXIT_STATE_FOR_CAMERA

```c
// 0xB2CBCD0930DFB420
bool CAN_SET_EXIT_STATE_FOR_CAMERA(bool HideNonRegisteredEntities);
```

Check that the camera is just about to exit the cut scene.


## Parameters
* **HideNonRegisteredEntities**: Can be used when cutting the camera on the exit state, in order to avoid issues with non script registered entities remaining on screen for a frame.
