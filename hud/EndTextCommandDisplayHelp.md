---
ns: HUD
aliases: ["0x238ffe5c7b0498a6"]
---
## END_TEXT_COMMAND_DISPLAY_HELP

```c
// 0x238FFE5C7B0498A6
void END_TEXT_COMMAND_DISPLAY_HELP(int iHelpId, bool DisplayForever, bool PlaySound, int OverrideDuration);
```

## Values for `iHelpId`:
| Value | Name |
| --- | --- |
| 0 | Standard |
| 1 | Floating 1 |
| 2 | Floating 2 |
| 3 | Floating 3 |


You can specify an OverrideDuration in milliseconds. Use the default of -1 to use the standard time which is based on the number of words

