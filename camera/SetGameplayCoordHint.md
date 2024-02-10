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
| 56 | No Fov / 1511508800 |
| 57 | Vehicle High Zoom 1726668277 |
| 58 | Arm3 Vehicle -244429742 |
| 59 | Agency Heist 3B Sky Diving 1213015174 |
| 60 | Family3 House Vehicle -1123838900 |
| 61 | Arm2 Mcs6 Vehicle 2010485655 |
| 62 | Killer Cam 1844968929 |
| 63 | Family3 Coach On Balcony Vehicle Hint Helper -87780624 |
| 64 | Chop Hint Helper 193150208 |


iDwellTime = how long cam looks at the entity.


## Parameters
* **vCoord**: 
* **iDwellTime**: 
* **iInterpTo**: How long the interp to the hint is
* **iInterpFrom**: How long the interp is from the iterp.
* **Type**: 
