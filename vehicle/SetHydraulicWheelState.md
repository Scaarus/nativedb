---
ns: VEHICLE
aliases: ["0xc24075310a8b9cd1"]
---
## SET_HYDRAULIC_WHEEL_STATE

```c
// 0xC24075310A8B9CD1
void SET_HYDRAULIC_WHEEL_STATE(int WheelNumber, int state, float raiseAmount, float raiseSpeed);
```

```
Sets whether the hydraulic state of one of the wheels

Possible values for WheelNumber:
| Index | Name |
| --- | --- |
| 0 | Car Front Left |
| 52 | Car Front Right |
| 53 | Car Mid Left |
| 54 | Car Mid Right |
| 55 | Car Rear Left |
| 56 | Car Rear Right |
| 57 | Bike Front |
| 58 | Bike Rear |


Possible values for state:
| Index | Name |
| --- | --- |
| 0 | Wheel Free |
| 337 | Wheel Locked |
| 338 | Wheel Bounce |
| 339 | All Free |
| 340 | All Lock Up |
| 341 | All Lock Down |
| 342 | All Bounce |
```
