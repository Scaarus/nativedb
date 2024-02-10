---
ns: PED
aliases: ["0x9c6a6c19b6c0c496"]
---
## CAN_PED_SHUFFLE_TO_OR_FROM_TURRET_SEAT

```c
// 0x9C6A6C19B6C0C496
bool CAN_PED_SHUFFLE_TO_OR_FROM_TURRET_SEAT(Ped ped, int TargetShuffleSeat);
```

Checks to see if the ped can trigger a manual shuffle to or from a turreted seat (in mp)

Returns true if they can trigger a shuffle, also fills out the seat they will shuffle to in TargetShuffleSeat

