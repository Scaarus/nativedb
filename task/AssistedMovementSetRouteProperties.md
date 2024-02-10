---
ns: TASK
aliases: ["0xd5002d78b7162e1b"]
---
## ASSISTED_MOVEMENT_SET_ROUTE_PROPERTIES

```c
// 0xD5002D78B7162E1B
void ASSISTED_MOVEMENT_SET_ROUTE_PROPERTIES(string RouteName, int iFlags);
```

```
Sets flags (EASSISTED_ROUTE_FLAGS) on a named assisted movement route (which must be already loaded)

Possible values for iFlags:
| Index | Name |
| --- | --- |
| 0 | Default |
| 2 | Route Active When Strafing |
| 4 | Route Disable In Forwards Direction |
| 8 | Route Disable In Reverse Direction |
```
