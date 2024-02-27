---
ns: PAD
aliases: ["0x6cd79468a1e595c6"]
---
## HAVE_CONTROLS_CHANGED

```c
// 0x6CD79468A1E595C6
bool HAVE_CONTROLS_CHANGED(int control);
```

Returns true if controls have changed since the last call to this function, this can happen if the user changes their control options, switches between FPS and TPS mode, or between gamepad and keyboardmouse.

## Values for `control`:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |

