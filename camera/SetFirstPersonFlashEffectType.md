---
ns: CAMERA
aliases: ["0x5c41e6babc9e2112"]
---
## SET_FIRST_PERSON_FLASH_EFFECT_TYPE

```c
// 0x5C41E6BABC9E2112
void SET_FIRST_PERSON_FLASH_EFFECT_TYPE(int type);
```

```
Sets the type of flash that will be initiated by a scripted camera blend out to first person this frame

Possible values for type:
| Index | Name |
| --- | --- |
| 0 | Neutral |
| 77 | Michael Michael'S Character Colour |
| 78 | Franklin Franklin'S Character Colour |
| 79 | Trevor Trevor'S Character Colour |


Must be called before RENDER_SCRIPT_CAMS(FALSE ) to change the type of the auto flash. Note that the auto flash will only happen if you specify an interpolation out of 300 ms or more in your RENDER_SCRIPT_CAMS call, and the player is set in first person mode.
```
