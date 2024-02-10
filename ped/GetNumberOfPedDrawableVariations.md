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

