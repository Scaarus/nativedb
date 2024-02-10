---
ns: AUDIO
aliases: ["0x5db8010ee71fdef2"]
---
## SET_VEHICLE_FORCE_REVERSE_WARNING

```c
// 0x5DB8010EE71FDEF2
void SET_VEHICLE_FORCE_REVERSE_WARNING(Vehicle vehicle, bool ForceReverseWarning);
```

```
Force the reversing beep to be active, even though the vehicle may not be in reverse gear (nb. the beep will not actually play unless the vehicle is also moving backwards)
```
