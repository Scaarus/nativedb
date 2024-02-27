---
ns: MISC
aliases: ["0x3f892caf67444ae7"]
---
## CREATE_INCIDENT

```c
// 0x3F892CAF67444AE7
bool CREATE_INCIDENT(Vector3 vLocation, int iNumUnits, float fTime, Incident incident, int iOverrideRelGroupHash, int assassinsLevel);
```

## Values for `assassinsLevel`:
| Value | Name |
| --- | --- |
| 0 | Med |
| 1 | Low |
| 2 | High |


- DISPATCH_TYPE is the type of units to be

Creates an incident and returns an index, requests a set number of units


## Parameters
* **vLocation**: 
* **iNumUnits**: 
* **fTime**: 
* **incident**: 
* **iOverrideRelGroupHash**: (Default value: `0`)
* **assassinsLevel**: (Default value: `0`)
