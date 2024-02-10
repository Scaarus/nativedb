---
ns: MISC
aliases: ["0x11db3500f042a8aa"]
---
## CLEAR_ANGLED_AREA_OF_VEHICLES

```c
// 0x11DB3500F042A8AA
void CLEAR_ANGLED_AREA_OF_VEHICLES(Vector3 vecAngledAreaPoint1, Vector3 vecAngledAreaPoint2, float DistanceOfOppositeFace, bool LeaveCarGenCars, bool Broadcast, bool CheckViewFrustum, bool IfWrecked, bool IfAbandoned, bool IfEngineOnFire, bool KeepScriptTrains);
```

Clears the non axis aligned area of all all non-mission vehicles ** CURRENTLY NOT SUPPORTED IN MP if Broadcast is set **


## Parameters
* **vecAngledAreaPoint1**: 
* **vecAngledAreaPoint2**: 
* **DistanceOfOppositeFace**: 
* **LeaveCarGenCars**: 
* **Broadcast**: if set an event is sent over the network in MP to do the same clear area on all other machines. Please avoid using this if you can.
* **CheckViewFrustum**: 
* **IfWrecked**: 
* **IfAbandoned**: 
* **IfEngineOnFire**: 
* **KeepScriptTrains**: 
