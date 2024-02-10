---
ns: MISC
aliases: ["0x957838aaf91bd12d"]
---
## CLEAR_AREA_LEAVE_VEHICLE_HEALTH

```c
// 0x957838AAF91BD12D
void CLEAR_AREA_LEAVE_VEHICLE_HEALTH(Vector3 CentrePosition, float Radius, bool DeleteProjectilesFlag, bool LeaveCarGenCars, bool ClearLowPriorityPickupsOnly, bool Broadcast);
```

Clears all non-mission cars and peds within the defined sphere but does not change the vehicle health

All projectiles in the world are removed if DeleteProjectilesFlag is set to TRUE.

All fires and explosions in the area are also cleared

