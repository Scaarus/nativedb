---
ns: VEHICLE
aliases: ["0x46e571a0e20d01f1"]
---
## IS_VEHICLE_WINDOW_INTACT

```c
// 0x46E571A0E20D01F1
bool IS_VEHICLE_WINDOW_INTACT(Vehicle vehicle, int WindowNumber);
```

```
Returns true if a window exists and is not smashed, false otherwise.

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
