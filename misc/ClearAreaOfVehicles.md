---
ns: MISC
aliases: ["0x01c7b9b38428aeb6"]
---
## CLEAR_AREA_OF_VEHICLES

```c
// 0x01C7B9B38428AEB6
void CLEAR_AREA_OF_VEHICLES(Vector3 CentrePosition, bool LeaveCarGenCars, bool CheckViewFrustum, bool IfWrecked, bool IfAbandoned, bool Broadcast, bool IfEngineOnFire, bool KeepScriptTrains);
```

Clears all non-mission vehicles within the defined sphere.


## Parameters
* **CentrePosition**: 
* **LeaveCarGenCars**: 
* **CheckViewFrustum**: 
* **IfWrecked**: 
* **IfAbandoned**: 
* **Broadcast**: if set an event is sent over the network in MP to do the same clear area on all other machines. Please avoid using this if you can.
* **IfEngineOnFire**: 
* **KeepScriptTrains**: 
