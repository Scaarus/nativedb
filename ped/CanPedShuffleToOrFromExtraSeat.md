---
ns: PED
aliases: ["0x2dfc81c9b9608549"]
---
## CAN_PED_SHUFFLE_TO_OR_FROM_EXTRA_SEAT

```c
// 0x2DFC81C9B9608549
bool CAN_PED_SHUFFLE_TO_OR_FROM_EXTRA_SEAT(Ped ped, int TargetShuffleSeat);
```

Checks to see if the ped can trigger a manual shuffle to or from a extra seat (in mp)

Returns true if they can trigger a shuffle, also fills out the seat they will shuffle to in TargetShuffleSeat

