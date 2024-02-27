---
ns: VEHICLE
aliases: ["0x46e571a0e20d01f1"]
---
## IS_VEHICLE_WINDOW_INTACT

```c
// 0x46E571A0E20D01F1
bool IS_VEHICLE_WINDOW_INTACT(Vehicle vehicle, int WindowNumber);
```

Returns true if a window exists and is not smashed, false otherwise.

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

