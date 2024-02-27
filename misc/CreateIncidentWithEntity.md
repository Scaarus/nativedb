---
ns: MISC
aliases: ["0x05983472f0494e60"]
---
## CREATE_INCIDENT_WITH_ENTITY

```c
// 0x05983472F0494E60
bool CREATE_INCIDENT_WITH_ENTITY(Entity entity, int iNumUnits, float fTime, Incident incident, int iOverrideRelGroupHash, int assassinsLevel);
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
* **entity**: 
* **iNumUnits**: 
* **fTime**: 
* **incident**: 
* **iOverrideRelGroupHash**: (Default value: `0`)
* **assassinsLevel**: (Default value: `0`)
