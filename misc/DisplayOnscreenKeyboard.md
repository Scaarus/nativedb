---
ns: MISC
aliases: ["0x00dc833f2568dbf6"]
---
## DISPLAY_ONSCREEN_KEYBOARD

```c
// 0x00DC833F2568DBF6
void DISPLAY_ONSCREEN_KEYBOARD(int keyboardTypeFlag, string prompt, string description, string initialValue1, string initialValue2, string initialValue3, string initialValue4, int maxLength);
```

```
Possible values for keyboardTypeFlag:
| Index | Name |
| --- | --- |
| 89 | English |
| 90 | Localised |
| 91 | Password |
| 92 | Gamertag |
| 93 | Email |
| 94 | Basic English |
| 95 | Filename |


Displays the system keyboard
```

## Parameters
* **keyboardTypeFlag**: 
* **prompt**: The prompt that the player sees initialValue1...
* **description**: this only has an effect on Xbox 360
* **initialValue1**: 
* **initialValue2**: 
* **initialValue3**: 
* **initialValue4**: The initial default text that the player sees. Up to four strings can be concatenated by this command to create one large initial string
* **maxLength**: the maximum number of characters that can be typed (
