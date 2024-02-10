---
ns: MISC
aliases: ["0xbe31fd6ce464ac59"]
---
## CLEAR_AREA_OF_PEDS

```c
// 0xBE31FD6CE464AC59
void CLEAR_AREA_OF_PEDS(Vector3 CentrePosition, float Radius, bool Broadcast);
```

```
Clears all non-mission peds within the defined sphere.
```

## Parameters
* **CentrePosition**: 
* **Radius**: 
* **Broadcast**: if set an event is sent over the network in MP to do the same clear area on all other machines. Please avoid using this if you can.
