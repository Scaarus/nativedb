---
ns: VEHICLE
aliases: ["0xc24075310a8b9cd1"]
---
## SET_HYDRAULIC_WHEEL_STATE

```c
// 0xC24075310A8B9CD1
void SET_HYDRAULIC_WHEEL_STATE(int WheelNumber, int state, float raiseAmount, float raiseSpeed);
```

Sets whether the hydraulic state of one of the wheels

## Values for `WheelNumber`:
| Value | Name |
| --- | --- |
| 0 | Car Front Left |
| 1 | Car Front Right |
| 2 | Car Mid Left |
| 3 | Car Mid Right |
| 4 | Car Rear Left |
| 5 | Car Rear Right |
| 6 | Bike Front |
| 7 | Bike Rear |


## Values for `state`:
| Value | Name |
| --- | --- |
| 0 | Wheel Free |
| 1 | Wheel Locked |
| 2 | Wheel Bounce |
| 3 | All Free |
| 4 | All Lock Up |
| 5 | All Lock Down |
| 6 | All Bounce |

