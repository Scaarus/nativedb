---
ns: STREAMING
aliases: ["0x5f2013f8bc24ee69"]
---
## SET_PLAYER_SHORT_SWITCH_STYLE

```c
// 0x5F2013F8BC24EE69
void SET_PLAYER_SHORT_SWITCH_STYLE(int style);
```

must be called AFTER [`START_PLAYER_SWITCH`](#_0xFAA23F2CBA159D67), overrides the style the short range player switch will use

## Values for `style`:
| Value | Name |
| --- | --- |
| 0 | Rotation |
| 1 | Translation |
| 2 | Zoom To Head |
| 3 | Zoom In Out |

