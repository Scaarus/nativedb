---
ns: MISC
aliases: ["0xb08b85d860e7ba3c"]
---
## SET_INCIDENT_REQUESTED_UNITS

```c
// 0xB08B85D860E7BA3C
void SET_INCIDENT_REQUESTED_UNITS(int dispatchType, int iNumUnits);
```

```
Possible values for dispatchType:
| Index | Name |
| --- | --- |
| 1 | Police Automobile |
| 41 | Police Helicopter |
| 42 | Fire Department |
| 43 | Swat Automobile |
| 44 | Ambulance Department |
| 45 | Police Riders |
| 46 | Police Vehicle Request |
| 47 | Police Road Block |
| 48 | Police Automobile Wait Pulled Over |
| 49 | Police Automobile Wait Cruising |
| 50 | Gangs |
| 51 | Swat Helicopter |
| 52 | Police Boat |
| 53 | Army Vehicle |
| 54 | Biker Backup |
| 55 | Assassins |


- DISPATCH_TYPE is the type of units to be

Updates the number of requested units of the given incident
```
