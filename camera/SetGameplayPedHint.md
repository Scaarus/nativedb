---
ns: CAMERA
aliases: ["0x2b486269acd548d3"]
---
## SET_GAMEPLAY_PED_HINT

```c
// 0x2B486269ACD548D3
void SET_GAMEPLAY_PED_HINT(Ped ped, Vector3 Offset, bool RelativeOffset, int iDwellTime, int iInterpTo, int iInterpFrom);
```

Sets the gameplay to hint a coord.

iDwellTime = how long cam looks at the entity. RelativeOffset : The offset is relative to the entity.


## Parameters
* **ped**: 
* **Offset**: 
* **RelativeOffset**: 
* **iDwellTime**: 
* **iInterpTo**: How long the interp to the hint is
* **iInterpFrom**: How long the interp is from the iterp.
