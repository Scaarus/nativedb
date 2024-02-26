---
ns: PED
aliases: ["0x27561561732a7842"]
---
## GET_NUMBER_OF_PED_DRAWABLE_VARIATIONS

```c
// 0x27561561732A7842
int GET_NUMBER_OF_PED_DRAWABLE_VARIATIONS(Ped ped, int ComponentNumber);
```

Gets the total number of different drawables for the specified part of the ped's body (component).

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

