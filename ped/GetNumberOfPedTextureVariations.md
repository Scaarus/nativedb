---
ns: PED
aliases: ["0x8f7156a3142a6bad"]
---
## GET_NUMBER_OF_PED_TEXTURE_VARIATIONS

```c
// 0x8F7156A3142A6BAD
int GET_NUMBER_OF_PED_TEXTURE_VARIATIONS(Ped ped, int ComponentNumber, int DrawableNumber);
```

Gets the total number of different textures for the specified drawable for the component (body part) for the ped's model.

## ComponentNumber Values:
| Value | Name |
| --- | --- |
| 0 | Head |
| 1 | Berd |
| 2 | Hair |
| 3 | Torso |
| 4 | Leg |
| 5 | Hand |
| 6 | Feet |
| 7 | Teeth |
| 8 | Special (Pv Comp Accs) |
| 9 | Special2 (Pv Comp Task) |
| 10 | Decl (?) |
| 11 | Jbib |


Each ped model can have several drawables for each component. Each drawable can have several textures.

