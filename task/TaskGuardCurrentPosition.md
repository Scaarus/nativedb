---
ns: TASK
aliases: ["0x4a58a47a72e3fcb4"]
---
## TASK_GUARD_CURRENT_POSITION

```c
// 0x4A58A47A72E3FCB4
void TASK_GUARD_CURRENT_POSITION(float fMaxPatrolProximity, float GuardAreaRadius, bool SetDefensiveArea);
```

Tells the ped to guard their current position with the area passed.

bSetDefensiveArea is set the peds defensive area will be set to the position and radius of fGuardAreaRadius. The behaviour will be the same as TASK_STAND_GUARD, but will only patrol inside the defensive area and inside fMaxPatrolProximity, if the ped shouldn't patrol the area, set fMaxPatrolProximity to 0.0

