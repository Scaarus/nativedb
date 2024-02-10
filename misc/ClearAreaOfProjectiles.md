---
ns: MISC
aliases: ["0x0a1cb9094635d1a6"]
---
## CLEAR_AREA_OF_PROJECTILES

```c
// 0x0A1CB9094635D1A6
void CLEAR_AREA_OF_PROJECTILES(Vector3 vPos, float fRadius, bool Broadcast);
```

Clears all projectiles within specified volume.


## Parameters
* **vPos**: 
* **fRadius**: 
* **Broadcast**: if set an event is sent over the network in MP to do the same clear area on all other machines. Please avoid using this if you can.
