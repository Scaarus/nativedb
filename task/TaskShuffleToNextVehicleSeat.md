---
ns: TASK
aliases: ["0x7aa80209bda643eb"]
---
## TASK_SHUFFLE_TO_NEXT_VEHICLE_SEAT

```c
// 0x7AA80209BDA643EB
void TASK_SHUFFLE_TO_NEXT_VEHICLE_SEAT(Vehicle vehicle, bool UseAlternateShuffle);
```

```
Tells the ped to move across to the next seat in the vehicle.

UseAlternateShuffle will lookup and use 'ShuffleLink2' defined in the vehicle layout, rather than the default shuffle link
```
