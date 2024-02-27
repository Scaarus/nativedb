---
ns: PED
aliases: ["0x04a355e041e004e6"]
---
## GET_PED_TEXTURE_VARIATION

```c
// 0x04A355E041E004E6
int GET_PED_TEXTURE_VARIATION(Ped ped, int ComponentNumber);
```

Gets the index of the current texture variation for the specified ped component (part of the body)

## Values for `ComponentNumber`:
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

