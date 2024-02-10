---
ns: MISC
aliases: ["0x3f892caf67444ae7"]
---
## CREATE_INCIDENT

```c
// 0x3F892CAF67444AE7
bool CREATE_INCIDENT(Vector3 vLocation, int iNumUnits, float fTime, int iOverrideRelGroupHash, int assassinsLevel);
```

## assassinsLevel Values:
| Value | Name |
| --- | --- |
| 1 | Low |
| 56 | Med |
| 57 | High |


- DISPATCH_TYPE is the type of units to be

Creates an incident and returns an index, requests a set number of units

