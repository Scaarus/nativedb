---
ns: PED
aliases: ["0x8f7156a3142a6bad"]
---
## GET_NUMBER_OF_PED_TEXTURE_VARIATIONS

```c
// 0x8F7156A3142A6BAD
int GET_NUMBER_OF_PED_TEXTURE_VARIATIONS(Ped ped, int ComponentNumber, int DrawableNumber);
```

```
Gets the total number of different textures for the specified drawable for the component (body part) for the ped's model.

Possible values for ComponentNumber:
| Index | Name |
| --- | --- |
| 0 | Head |
| 139 | Berd |
| 140 | Hair |
| 141 | Torso |
| 142 | Leg |
| 143 | Hand |
| 144 | Feet |
| 145 | Teeth |
| 146 | Special Pv Comp Accs |
| 147 | Special2 Pv Comp Task |
| 148 | Decl ? |
| 149 | Jbib |


Each ped model can have several drawables for each component. Each drawable can have several textures.
```
