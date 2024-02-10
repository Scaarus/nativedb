---
ns: STREAMING
aliases: ["0x470555300d10b2a5"]
---
## GET_PLAYER_SWITCH_STATE

```c
// 0x470555300D10B2A5
switch_state GET_PLAYER_SWITCH_STATE();
```

returns current state of player switch, as per enum SWITCH_STATE

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Intro |
| 1 | Prep Descent |
| 2 | Prep For Cut |
| 3 | Jumpcut Ascent |
| 4 | Waitforinput Intro |
| 5 | Waitforinput |
| 6 | Waitforinput Outro |
| 7 | Pan |
| 8 | Jumpcut Descent |
| 9 | Outro Hold |
| 10 | Outro Swoop |
| 11 | Establishing Shot |
| 12 | Finished |
| 13 | Outro |

