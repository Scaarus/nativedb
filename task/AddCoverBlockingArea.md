---
ns: TASK
aliases: ["0x45c597097dd7cb81"]
---
## ADD_COVER_BLOCKING_AREA

```c
// 0x45C597097DD7CB81
void ADD_COVER_BLOCKING_AREA(Vector3 vEnd, bool BlockObjects, bool BlockVehicles, bool BlockMap, bool BlockPlayer);
```

Adds an axis aligned area that will block coverpoints from being automatically created.

if you want them to use scripted points added instead. You must call REMOVE_ALL_COVER_BLOCKING_AREAS at the end of the mission to remove them, this command can only be used during mission scripts MAX allowed areas is 16. Let code know if that needs increasing

