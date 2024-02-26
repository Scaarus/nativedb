---
ns: CAMERA
aliases: ["0x21e253a7f8da5dfb"]
---
## SET_FIRST_PERSON_FLASH_EFFECT_VEHICLE_MODEL_NAME

```c
// 0x21E253A7F8DA5DFB
void SET_FIRST_PERSON_FLASH_EFFECT_VEHICLE_MODEL_NAME(string modelName);
```

Sets the vehicle model name used to calculate first person camera settings for a first person flash triggered by scripted cameras this frame.

Must be called before [RENDER_SCRIPT_CAMS](#_0x07E5B515DB0636FC)(FALSE ) when you're going to warp the ped into a vehicle on the camera cut the flash corresponds to. Note that the auto flash will only happen if you specify an interpolation out of 300 ms or more in your RENDER_SCRIPT_CAMS call, and the player is set in first person mode.

