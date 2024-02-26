---
ns: VEHICLE
aliases: ["0x602e548f46e24d59"]
---
## ROLL_UP_WINDOW

```c
// 0x602E548F46E24D59
void ROLL_UP_WINDOW(Vehicle vehicle, int WindowNumber);
```

Rolls up a given vehicle window. NB - it only snaps the window up. Probably want to do this off-screen.

## WindowNumber Values:
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

