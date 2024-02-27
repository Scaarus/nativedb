---
ns: PAD
aliases: ["0x80c2fd58d720c801"]
---
## GET_CONTROL_GROUP_INSTRUCTIONAL_BUTTONS_STRING

```c
// 0x80C2FD58D720C801
string GET_CONTROL_GROUP_INSTRUCTIONAL_BUTTONS_STRING(int control, int actionGroup, bool allowXOSwap);
```

Return an encoded string of the icon to show of a CONTROL_ACTION. empty string will be returned on error!

## control Values:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |


## actionGroup Values:
| Value | Name |
| --- | --- |
| 0 | Move |
| 1 | Look |
| 2 | Wheel |
| 3 | Cellphone Navigate |
| 4 | Cellphone Navigate Ud |
| 5 | Cellphone Navigate Lr |
| 6 | Frontend Dpad All |
| 7 | Frontend Dpad Ud |
| 8 | Frontend Dpad Lr |
| 9 | Frontend Lstick All |
| 10 | Frontend Rstick All |
| 11 | Frontend Generic Ud |
| 12 | Frontend Generic Lr |
| 13 | Frontend Generic All |
| 14 | Frontend Bumpers |
| 15 | Frontend Triggers |
| 16 | Frontend Sticks |
| 17 | Script Dpad All |
| 18 | Script Dpad Ud |
| 19 | Script Dpad Lr |
| 20 | Script Lstick All |
| 21 | Script Rstick All |
| 22 | Script Bumpers |
| 23 | Script Triggers |
| 24 | Weapon Wheel Cycle |
| 25 | Fly |
| 26 | Sub |
| 27 | Veh Move All |
| 28 | Cursor |
| 29 | Cursor Scroll |
| 30 | Sniper Zoom Secondary |
| 31 | Veh Hydraulics Control |


## Parameters
* **control**: 
* **actionGroup**: 
* **allowXOSwap**: (Default value: `True`)
