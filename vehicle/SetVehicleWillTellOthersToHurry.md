---
ns: VEHICLE
aliases: ["0x2c4a1590abf43e8b"]
---
## SET_VEHICLE_WILL_TELL_OTHERS_TO_HURRY

```c
// 0x2C4A1590ABF43E8B
void SET_VEHICLE_WILL_TELL_OTHERS_TO_HURRY(Vehicle vehicle, bool TellOthersToHurry);
```

Makes this vehicle cause ambient vehicles that get in its way to hurry away. Does not affect mission vehicles

This is a reset flag, it must be called each frame

