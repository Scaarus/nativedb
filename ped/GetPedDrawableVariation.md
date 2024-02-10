---
ns: PED
aliases: ["0x67f3780dd425d4fc"]
---
## GET_PED_DRAWABLE_VARIATION

```c
// 0x67F3780DD425D4FC
int GET_PED_DRAWABLE_VARIATION(Ped ped, int ComponentNumber);
```

Gets the index of the current drawable (geometry) for the specified part of the ped's body (component). More infp..

## ComponentNumber Values:
| Value | Name |
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

