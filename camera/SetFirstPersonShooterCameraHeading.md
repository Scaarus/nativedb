---
ns: CAMERA
aliases: ["0x103991d4a307d472"]
---
## SET_FIRST_PERSON_SHOOTER_CAMERA_HEADING

```c
// 0x103991D4A307D472
void SET_FIRST_PERSON_SHOOTER_CAMERA_HEADING(float heading);
```

```
Sets the first person shooter camera heading. If the camera does not exist, this heading will be used when it is created.

If the first person shooter camera is active, does the same thing as SET_GAMEPLAY_CAM_RELATIVE_HEADING. If not active, the heading will be set when the camera is created.
```

## Parameters
* **heading**: The relative heading to set, in degrees.
