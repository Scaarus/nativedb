---
ns: CAMERA
aliases: ["0x11fa5d3479c7dd47"]
---
## SET_FIRST_PERSON_FLASH_EFFECT_VEHICLE_MODEL_HASH

```c
// 0x11FA5D3479C7DD47
void SET_FIRST_PERSON_FLASH_EFFECT_VEHICLE_MODEL_HASH(int modelHash);
```

Sets the vehicle model hash used to calculate first person camera settings for a first person flash triggered by scripted cameras this frame.

Must be called before [`RENDER_SCRIPT_CAMS`](#_0x07E5B515DB0636FC)(FALSE ) when you're going to warp the ped into a vehicle on the camera cut the flash corresponds to. Note that the auto flash will only happen if you specify an interpolation out of 300 ms or more in your RENDER_SCRIPT_CAMS call, and the player is set in first person mode.

