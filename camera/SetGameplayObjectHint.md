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
* **RelativeOffset**: (Default value: `True`)
* **iDwellTime**: (Default value: `Default_Dwell_Time`)
* **iInterpTo**: How long the interp to the hint is (Default value: `Default_Interp_In_Time`)
* **iInterpFrom**: How long the interp is from the iterp. (Default value: `Default_Interp_Out_Time`)
