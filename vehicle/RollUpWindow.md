---
ns: VEHICLE
aliases: ["0x602e548f46e24d59"]
---
## ROLL_UP_WINDOW

```c
// 0x602E548F46E24D59
void ROLL_UP_WINDOW(Vehicle vehicle, int WindowNumber);
```

```
Rolls up a given vehicle window. NB - it only snaps the window up. Probably want to do this off-screen.

Possible values for WindowNumber:
| Index | Name |
| --- | --- |
| 0 | Ow Front Left |
| 66 | Ow Front Right |
| 67 | Ow Rear Left |
| 68 | Ow Rear Right |
| 69 | Ow Middle Left |
| 70 | Ow Middle Right |
| 71 | Screen Front |
| 72 | Screen Rear |
```
