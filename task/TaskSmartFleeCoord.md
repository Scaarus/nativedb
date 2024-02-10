---
ns: TASK
aliases: ["0x94587f17e9c365d5"]
---
## TASK_SMART_FLEE_COORD

```c
// 0x94587F17E9C365D5
void TASK_SMART_FLEE_COORD(Ped ped, Vector3 Position, float SafeDistance, int FleeTime, bool PreferPavements, bool QuitIfOutOfRange);
```

Tells a ped to flee the given coord.

FleeTime is an INT (-1 indicates flee forever)

