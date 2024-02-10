---
ns: TASK
aliases: ["0xd2a207eebdf9889b"]
---
## TASK_GUARD_ASSIGNED_DEFENSIVE_AREA

```c
// 0xD2A207EEBDF9889B
void TASK_GUARD_ASSIGNED_DEFENSIVE_AREA(Vector3 vDefendPosition, float fHeading, float fMaxPatrolProximity, int nTimer);
```

Tells the ped to guard its assigned area, will assert if no defensive area is assigned.

The behaviour will be the same as TASK_STAND_GUARD, if the ped shouldn't patrol the area, set fMaxPatrolProximity to 0.0

