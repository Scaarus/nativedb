---
ns: VEHICLE
aliases: ["0x7ad9e6ce657d69e3"]
---
## ROLL_DOWN_WINDOW

```c
// 0x7AD9E6CE657D69E3
void ROLL_DOWN_WINDOW(Vehicle vehicle, int WindowNumber);
```

Rolls down a given vehicle window. NB - it only snaps the window down. Probably want to do this off-screen.

## Values for `WindowNumber`:
| Value | Name |
| --- | --- |
| 0 | SC_WINDOW_FRONT_LEFT |
| 1 | SC_WINDOW_FRONT_RIGHT |
| 2 | SC_WINDOW_REAR_LEFT |
| 3 | SC_WINDOW_REAR_RIGHT |
| 4 | SC_WINDOW_MIDDLE_LEFT |
| 5 | SC_WINDOW_MIDDLE_RIGHT |
| 6 | SC_WINDSCREEN_FRONT |
| 7 | SC_WINDSCREEN_REAR |

