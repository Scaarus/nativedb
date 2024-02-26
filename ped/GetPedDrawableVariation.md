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

