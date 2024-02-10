---
ns: CAMERA
aliases: ["0x83e87508a2ca2ac6"]
---
## SET_GAMEPLAY_OBJECT_HINT

```c
// 0x83E87508A2CA2AC6
void SET_GAMEPLAY_OBJECT_HINT(Object object, Vector3 Offset, bool RelativeOffset, int iDwellTime, int iInterpTo, int iInterpFrom);
```

Sets the gameplay to hint a coord.

iDwellTime = how long cam looks at the entity. RelativeOffset : The offset is relative to the entity.


## Parameters
* **object**: 
* **Offset**: 
* **RelativeOffset**: 
* **iDwellTime**: 
* **iInterpTo**: How long the interp to the hint is
* **iInterpFrom**: How long the interp is from the iterp.
