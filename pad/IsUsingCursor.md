---
ns: PAD
aliases: ["0x13337b38db572509"]
---
## IS_USING_CURSOR

```c
// 0x13337B38DB572509
bool IS_USING_CURSOR(int control);
```

Returns true if the cursor CONTROL_ACTIONS are valid (e.g. on a touchpad, the touchpad is actually being touched).
When this returns false, the values inside the cursor CONTROL_ACTIONS will be zero.

## control Values:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |

