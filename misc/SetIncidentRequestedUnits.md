---
ns: MISC
aliases: ["0xb08b85d860e7ba3c"]
---
## SET_INCIDENT_REQUESTED_UNITS

```c
// 0xB08B85D860E7BA3C
void SET_INCIDENT_REQUESTED_UNITS(int dispatchType, int iNumUnits);
```

## Values for `dispatchType`:
| Value | Name |
| --- | --- |
| 0 | Police Helicopter |
| 1 | Police Automobile |
| 2 | Fire Department |
| 3 | Swat Automobile |
| 4 | Ambulance Department |
| 5 | Police Riders |
| 6 | Police Vehicle Request |
| 7 | Police Road Block |
| 8 | Police Automobile Wait Pulled Over |
| 9 | Police Automobile Wait Cruising |
| 10 | Gangs |
| 11 | Swat Helicopter |
| 12 | Police Boat |
| 13 | Army Vehicle |
| 14 | Biker Backup |
| 15 | Assassins |


- DISPATCH_TYPE is the type of units to be

Updates the number of requested units of the given incident

