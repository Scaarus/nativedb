---
ns: VEHICLE
aliases: ["0x1f9fb66f3a3842d2"]
---
## SET_VEHICLE_ACT_AS_IF_HIGH_SPEED_FOR_FRAG_SMASHING

```c
// 0x1F9FB66F3A3842D2
void SET_VEHICLE_ACT_AS_IF_HIGH_SPEED_FOR_FRAG_SMASHING(Vehicle vehicle, bool ActHighSpeed);
```

```
Call this to set a vehicle to act as if it has a very high speed when colliding with a frag. Mostly useful for scripted sequencse where a vehicle needs to break through a barrier, but may not be going fast enough to break it

You should never need to pass in false here, since the flag resets itself after the frame

This is a reset flag, and will only stay set for one frame
```
