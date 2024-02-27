---
ns: VEHICLE
aliases: ["0x877c1eaeac531023"]
---
## SET_PICKUP_ROPE_LENGTH_FOR_CARGOBOB

```c
// 0x877C1EAEAC531023
void SET_PICKUP_ROPE_LENGTH_FOR_CARGOBOB(Vehicle vehicle, float detachedRopeLength, float attachedRopeLength, bool SetRopeLengthInstantly);
```

Generate the pick up rope for cargobob


## Parameters
* **vehicle**: 
* **detachedRopeLength**: Desired rope length when nothing is attached to the rope
* **attachedRopeLength**: Desired rope length when rope is attached to something
* **SetRopeLengthInstantly**: (Default value: `False`)
