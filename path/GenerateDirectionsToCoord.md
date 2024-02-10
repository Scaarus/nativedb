---
ns: PATH
aliases: ["0xf90125f1f79ecdf8"]
---
## GENERATE_DIRECTIONS_TO_COORD

```c
// 0xF90125F1F79ECDF8
int GENERATE_DIRECTIONS_TO_COORD(Vector3 vDestination, int iFlags);
```

iFlags is currently unused, and should be set to zero iDirections is returned by parameter, and will be a value from the VEHICLE_PATH_DIRECTIONS enumeration In the case of a junction being identified, fApproxDistance will be non-zero RETURN : the return value is not currently used, but left for future expansion

Performs a path search, and attempts to identify the next direction which needs to be taken to follow the route to the target

