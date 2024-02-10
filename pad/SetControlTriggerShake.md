---
ns: PAD
aliases: ["0x14d29bb12d47f68c"]
---
## SET_CONTROL_TRIGGER_SHAKE

```c
// 0x14D29BB12D47F68C
void SET_CONTROL_TRIGGER_SHAKE(int control, int leftDuration, int leftFrequency, int rightDuration, int rightFrequency);
```

```
Causes the given Pad, assigned to a Control, to shake its triggers.

Possible values for control:
| Index | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |


Frequency should be less than 256. Duration is in milliseconds
```
