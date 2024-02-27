---
ns: PAD
aliases: ["0x48b3886c1358d0d5"]
---
## SET_CONTROL_SHAKE

```c
// 0x48B3886C1358D0D5
void SET_CONTROL_SHAKE(int control, int Duration, int Frequency);
```

Causes the given Pad, assigned to a Control, to shake.

## Values for `control`:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |


Frequency should be less than 256. Duration is in milliseconds

