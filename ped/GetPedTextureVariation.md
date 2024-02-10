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

