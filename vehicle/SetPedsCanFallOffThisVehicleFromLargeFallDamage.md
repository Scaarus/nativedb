---
ns: VEHICLE
aliases: ["0x59c3757b3b7408e8"]
---
## SET_PEDS_CAN_FALL_OFF_THIS_VEHICLE_FROM_LARGE_FALL_DAMAGE

```c
// 0x59C3757B3B7408E8
void SET_PEDS_CAN_FALL_OFF_THIS_VEHICLE_FROM_LARGE_FALL_DAMAGE(Vehicle vehicle, bool Enable, float fVelThreshold);
```

```
Call this on a bike / quad every frame to change the likelihood that peds will be knocked off after a heavy fall.

Any negative value of fVelThreshold will leave the default value for this vehicle. The higher the positive value, the greater the fall that the bike quad can sustain before the passengers are knocked off.

These values are reset and will only stay set for one frame.
```
