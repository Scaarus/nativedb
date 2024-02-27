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
| 0 | English |
| 1 | Localised |
| 2 | Password |
| 3 | Gamertag |
| 4 | Email |
| 5 | Basic English |
| 6 | Filename |


Variant of [`DISPLAY_ONSCREEN_KEYBOARD`](#_0x00DC833F2568DBF6) which takes up to eight strings to support an initial value of 500 characters

