---
ns: PED
aliases: ["0xb282749d5e028163"]
---
## SET_PED_CAN_BE_KNOCKED_OFF_BIKE

```c
// 0xB282749D5E028163
void SET_PED_CAN_BE_KNOCKED_OFF_BIKE(Ped ped, int CanBeKnockedOffFlag);
```

```
Sets that a ped can be knocked off.

Possible values for CanBeKnockedOffFlag:
| Index | Name |
| --- | --- |
| 0 | Default |
| 125 | Never |
| 126 | Easy |
| 127 | Hard |


BIKE_KNOCKOFF in commands_ped.sch
```
