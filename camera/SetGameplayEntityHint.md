---
ns: CAMERA
aliases: ["0x189e955a8313e298"]
---
## SET_GAMEPLAY_ENTITY_HINT

```c
// 0x189E955A8313E298
void SET_GAMEPLAY_ENTITY_HINT(Entity entity, Vector3 Offset, bool RelativeOffset, int iDwellTime, int iInterpTo, int iInterpFrom);
```

Sets the gameplay to hint a coord.

iDwellTime = how long cam looks at the entity. RelativeOffset : The offset is relative to the entity.


## Parameters
* **entity**: 
* **Offset**: 
* **RelativeOffset**: (Default value: `True`)
* **iDwellTime**: (Default value: `Default_Dwell_Time`)
* **iInterpTo**: How long the interp to the hint is (Default value: `Default_Interp_In_Time`)
* **iInterpFrom**: How long the interp is from the iterp. (Default value: `Default_Interp_Out_Time`)
