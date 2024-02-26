---
ns: PAD
aliases: ["0xf239400e16c23e08"]
---
## SET_CONTROL_SHAKE_SUPPRESSED_ID

```c
// 0xF239400E16C23E08
void SET_CONTROL_SHAKE_SUPPRESSED_ID(int control, int SupressId);
```

Suppresses vibrations on a given control's pad when id set to other than -1, clear on -1 or call [CLEAR_CONTROL_SHAKE_SUPPRESSED_ID](#_0xA0CEFCEA390AAB9B).

## control Values:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |

