---
ns: TASK
aliases: ["0xc946fe14be0eb5e2"]
---
## TASK_GUARD_SPHERE_DEFENSIVE_AREA

```c
// 0xC946FE14BE0EB5E2
void TASK_GUARD_SPHERE_DEFENSIVE_AREA(Ped ped, Vector3 vDefendPosition, float fHeading, float fMaxPatrolProximity, int nTimer, Vector3 vAreaStart, float fAreaRadius);
```

Sets the defensive area of the ped and tells the ped to guard the area passed.

The behaviour will be the same as [`TASK_STAND_GUARD`](#_0xAE032F8BBA959E90), but will only patrol inside the defensive area and inside fMaxPatrolProximity, if the ped shouldn't patrol the area, set fMaxPatrolProximity to 0.0 The area is specified using vAreaCentre and fAreaRadius the same format as SET_PED_SPHERE_DEFENSIVE_AREA.

