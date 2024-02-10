---
ns: MISC
aliases: ["0xa56f01f3765b93a0"]
---
## CLEAR_AREA

```c
// 0xA56F01F3765B93A0
void CLEAR_AREA(Vector3 CentrePosition, float Radius, bool DeleteProjectilesFlag, bool LeaveCarGenCars, bool ClearLowPriorityPickupsOnly, bool Broadcast);
```

```
Clears all non-mission cars and peds within the defined sphere.

All projectiles in the world are removed if DeleteProjectilesFlag is set to TRUE.

All fires and explosions in the area are also cleared
```
