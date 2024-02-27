---
ns: MISC
aliases: ["0x04f8fc8fcf58f88d"]
---
## CLEAR_AREA_OF_COPS

```c
// 0x04F8FC8FCF58F88D
void CLEAR_AREA_OF_COPS(Vector3 CentrePosition, float Radius, bool Broadcast);
```

Clears all non-mission cops within the defined sphere.


## Parameters
* **CentrePosition**: 
* **Radius**: 
* **Broadcast**: if set an event is sent over the network in MP to do the same clear area on all other machines. Please avoid using this if you can. (Default value: `False`)
