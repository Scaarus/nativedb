---
ns: PED
aliases: ["0xe3dd5f2a84b42281"]
---
## GET_PED_PALETTE_VARIATION

```c
// 0xE3DD5F2A84B42281
int GET_PED_PALETTE_VARIATION(Ped ped, int ComponentNumber);
```

```
Returns the index of the current palette variation for the current drawable of the specified component.

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


The returned palette index will be between 0 and 15.
```
