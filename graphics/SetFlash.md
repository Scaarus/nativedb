---
ns: GRAPHICS
aliases: ["0x0ab84296fed9cfc6"]
---
## SET_FLASH

```c
// 0x0AB84296FED9CFC6
void SET_FLASH(float MinExposure, float fMaxExposure, int rampUpDuration, int rampDownDuration, int holdDuration);
```

```
Trigger a one-off screen flash

MinExposure minimum exposure to add to current exposure, can be zero, will be applied during the entire flash effect. MaxExposure maximum exposure to add to current exposure, will ramp updown tofrom this value, this will be the value added during the hold phase. rampUpDuration time, in milliseconds to ramp up from MinExposure to MaxExposure holdDuration time, in milliseconds to to hold at MaxExposure rampDownDuration time, in milliseconds to ramp down from MaxExposure to MinExposure
```
