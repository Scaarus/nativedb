---
ns: MISC
aliases: ["0x05983472f0494e60"]
---
## CREATE_INCIDENT_WITH_ENTITY

```c
// 0x05983472F0494E60
bool CREATE_INCIDENT_WITH_ENTITY(Entity entity, int iNumUnits, float fTime, int iOverrideRelGroupHash, int assassinsLevel);
```

## assassinsLevel Values:
| Value | Name |
| --- | --- |
| 1 | Low |
| 56 | Med |
| 57 | High |


- DISPATCH_TYPE is the type of units to be

Creates an incident and returns an index, requests a set number of units
