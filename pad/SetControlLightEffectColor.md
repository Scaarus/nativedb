---
ns: PAD
aliases: ["0x8290252fff36acb5"]
---
## SET_CONTROL_LIGHT_EFFECT_COLOR

```c
// 0x8290252FFF36ACB5
void SET_CONTROL_LIGHT_EFFECT_COLOR(int control, int red, int green, int blue);
```

Sets a light device to a constant color (if there is one).

## Values for `control`:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |

