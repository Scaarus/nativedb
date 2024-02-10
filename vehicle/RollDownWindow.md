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

## WindowNumber Values:
| Value | Name |
| --- | --- |
| 0 | Ow Front Left |
| 66 | Ow Front Right |
| 67 | Ow Rear Left |
| 68 | Ow Rear Right |
| 69 | Ow Middle Left |
| 70 | Ow Middle Right |
| 71 | Screen Front |
| 72 | Screen Rear |

