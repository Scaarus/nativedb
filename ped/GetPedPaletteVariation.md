---
ns: PED
aliases: ["0xe3dd5f2a84b42281"]
---
## GET_PED_PALETTE_VARIATION

```c
// 0xE3DD5F2A84B42281
int GET_PED_PALETTE_VARIATION(Ped ped, int ComponentNumber);
```

Returns the index of the current palette variation for the current drawable of the specified component.

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


The returned palette index will be between 0 and 15.

