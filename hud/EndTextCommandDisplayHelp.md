---
ns: HUD
aliases: ["0x238ffe5c7b0498a6"]
---
## END_TEXT_COMMAND_DISPLAY_HELP

```c
// 0x238FFE5C7B0498A6
void END_TEXT_COMMAND_DISPLAY_HELP(int iHelpId, bool DisplayForever, bool PlaySound, int OverrideDuration);
```

```
Possible values for iHelpId:
| Index | Name |
| --- | --- |
| 0 | HELP_TEXT_SLOT_STANDARD |
| 1193 | HELP_TEXT_SLOT_FLOATING_1 |
| 1194 | HELP_TEXT_SLOT_FLOATING_2 |
| 1195 | HELP_TEXT_SLOT_FLOATING_3 |
| 1196 | MAX_HELP_TEXT_SLOTS |


can specify an OverrideDuration in milliseconds. Use the default of -1 to use the standard time which is based on the number of words
```
