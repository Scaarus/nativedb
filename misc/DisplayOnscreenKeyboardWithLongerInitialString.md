---
ns: MISC
aliases: ["0xca78cfa0366592fe"]
---
## DISPLAY_ONSCREEN_KEYBOARD_WITH_LONGER_INITIAL_STRING

```c
// 0xCA78CFA0366592FE
void DISPLAY_ONSCREEN_KEYBOARD_WITH_LONGER_INITIAL_STRING(int keyboardTypeFlag, string prompt, string description, string initialValue1, string initialValue2, string initialValue3, string initialValue4, string initialValue5, string initialValue6, string initialValue7, string initialValue8, int maxLength);
```

## keyboardTypeFlag Values:
| Value | Name |
| --- | --- |
| 89 | English |
| 90 | Localised |
| 91 | Password |
| 92 | Gamertag |
| 93 | Email |
| 94 | Basic English |
| 95 | Filename |


Variant of DISPLAY_ONSCREEN_KEYBOARD which takes up to eight strings to support an initial value of 500 characters

