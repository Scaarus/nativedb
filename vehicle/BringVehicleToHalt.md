---
ns: VEHICLE
aliases: ["0x260be8f09e326a20"]
---
## BRING_VEHICLE_TO_HALT

```c
// 0x260BE8F09E326A20
void BRING_VEHICLE_TO_HALT(Vehicle vehicle, float StoppingDistance, int nTimeToStopFor, bool ControlVerticalVelocity);
```

Decelerates a vehicle until it comes to rest, possibly in an unphysically short distance.


## Parameters
* **vehicle**: 
* **StoppingDistance**: the distance from the initial coords at which the vehicle should come to rest.
* **nTimeToStopFor**: the length of time in seconds to hold the car at rest after stopping.
* **ControlVerticalVelocity**: 
