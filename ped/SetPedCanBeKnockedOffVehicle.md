---
ns: PED
aliases: ["0x7a6535691b477c48"]
---
## SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE

```c
// 0x7A6535691B477C48
void SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE(Ped ped, int CanBeKnockedOffFlag);
```

Sets that a ped can be knocked off.

## Values for `CanBeKnockedOffFlag`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Never |
| 2 | Easy |
| 3 | Hard |


VEHICLE_KNOCKOFF in commands_ped.sch

