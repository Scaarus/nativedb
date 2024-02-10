---
ns: MISC
aliases: ["0x3ed1438c1f5c6612"]
---
## NEXT_ONSCREEN_KEYBOARD_RESULT_WILL_DISPLAY_USING_THESE_FONTS

```c
// 0x3ED1438C1F5C6612
void NEXT_ONSCREEN_KEYBOARD_RESULT_WILL_DISPLAY_USING_THESE_FONTS(int fontBitField);
```

```
Possible values for fontBitField:
| Index | Name |
| --- | --- |
| 2 | Cursive |
| 4 | Rockstar Tag |
| 8 | Leaderboard |
| 16 | Condensed |
| 32 | Fixed Width Numbers |
| 64 | Condensed Not Gamername |
| 128 | Pricedown |


Call this command before displaying the onscreen keyboard so that any characters that aren't supported in all the fonts can be replaced with a space character. The bit field will only apply to the next time the onscreen keyboard is displayed.
```
