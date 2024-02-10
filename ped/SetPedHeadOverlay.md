---
ns: PED
aliases: ["0x48f44967fa05cc1e"]
---
## SET_PED_HEAD_OVERLAY

```c
// 0x48F44967FA05CC1E
void SET_PED_HEAD_OVERLAY(Ped ped, int slot, int tex, float blend);
```

Sets an overlay texture for the blended head of the given ped.

## slot Values:
| Value | Name |
| --- | --- |
| 0 | Blemishes |
| 1 | Facial Hair |
| 2 | Eyebrow |
| 3 | Aging |
| 4 | Makeup |
| 5 | Blusher |
| 6 | Damage |
| 7 | Base Detail |
| 8 | Skin Detail 1 |
| 9 | Skin Detail 2 |
| 10 | Body 1 |
| 11 | Body 2 |
| 12 | Body 3 |


This function sets an overlay texture on a blended head. The ped index given needs to be an MP ped with a blended head, which means SET_PED_HEAD_BLEND_DATA needs to have already been called on this ped before this function is called.


## Parameters
* **ped**: 
* **slot**: The slot to set the overlay texture on, can be any of the
* **tex**: index of overlay texture. use GET_PED_HEAD_OVERLAY_NUM to get the count for the slot
* **blend**: the blend strength of the overlay. 0.0 = blend not visible, 1.0 = blend fully visible
