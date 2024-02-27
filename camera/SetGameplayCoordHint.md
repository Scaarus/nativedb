---
ns: CAMERA
aliases: ["0xd51adcd2d8bc0fb3"]
---
## SET_GAMEPLAY_COORD_HINT

```c
// 0xD51ADCD2D8BC0FB3
void SET_GAMEPLAY_COORD_HINT(Vector3 vCoord, int iDwellTime, int iInterpTo, int iInterpFrom, int Type);
```

Sets the gameplay to hint a coord.

## Type Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | No Fov (/ 1511508800) |
| 2 | Vehicle High Zoom (1726668277) |
| 3 | Arm3 Vehicle (-244429742) |
| 4 | Agency Heist 3B Sky Diving (1213015174) |
| 5 | Family3 House Vehicle (-1123838900) |
| 6 | Arm2 Mcs6 Vehicle (2010485655) |
| 7 | Killer Cam (1844968929) |
| 8 | Family3 Coach On Balcony Vehicle Hint Helper (-87780624) |
| 9 | Chop Hint Helper (193150208) |


iDwellTime = how long cam looks at the entity.


## Parameters
* **vCoord**: 
* **iDwellTime**: (Default value: `Default_Dwell_Time`)
* **iInterpTo**: How long the interp to the hint is (Default value: `Default_Interp_In_Time`)
* **iInterpFrom**: How long the interp is from the iterp. (Default value: `Default_Interp_Out_Time`)
* **Type**: (Default value: `Default`)
