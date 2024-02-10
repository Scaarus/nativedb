---
ns: CAMERA
aliases: ["0xa2297e18f3e71c2e"]
---
## SET_GAMEPLAY_VEHICLE_HINT

```c
// 0xA2297E18F3E71C2E
void SET_GAMEPLAY_VEHICLE_HINT(Vehicle vehicle, Vector3 Offset, bool RelativeOffset, int iDwellTime, int iInterpTo, int iInterpFrom);
```

Sets the gameplay to hint a coord.

iDwellTime = how long cam looks at the entity. RelativeOffset : The offset is relative to the entity.


## Parameters
* **vehicle**: 
* **Offset**: 
* **RelativeOffset**: 
* **iDwellTime**: 
* **iInterpTo**: How long the interp to the hint is
* **iInterpFrom**: How long the interp is from the iterp.
