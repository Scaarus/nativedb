---
ns: PAD
aliases: ["0x7f4724035fdca1dd"]
---
## ALLOW_ALTERNATIVE_SCRIPT_CONTROLS_LAYOUT

```c
// 0x7F4724035FDCA1DD
void ALLOW_ALTERNATIVE_SCRIPT_CONTROLS_LAYOUT(int control);
```

Switches INPUT_SCRIPT_* controls to use alternative layouts.

This must be called every frame or else the controls revert back to defaults. The INPUT_SCRIPT_* controls mimic a PS3/Xbox gamepad, however, the user may change the control layout in the settings. Some missionscript might need to know this. For example, if the INPUT_SCRIPT_* controls are being used to control movement and the camera, then the script need to know if the player has selected Southpaw (sticks are swapped) mode. Calling ALLOW_ALTERNATIVE_SCRIPT_CONTROLS_LAYOUT() every frame will calculate this for you so you can carry on using the INPUT_SCRIPT_* controls as if they were the standard layout when infact they are actually altered to reflect the user preferences. Some scriptsmission will *NOT* want this, for example, Yoga asks the user to move specific sticks. In this case, not calling ALLOW_ALTERNATIVE_SCRIPT_CONTROLS_LAYOUT() will default to use the standard gamepad layout no matter what the user has set their settings to.

## Values for `control`:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |

