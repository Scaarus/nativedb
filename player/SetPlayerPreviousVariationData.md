---
ns: PLAYER
aliases: ["0x7bae68775557ae0b"]
---
## SET_PLAYER_PREVIOUS_VARIATION_DATA

```c
// 0x7BAE68775557AE0B
void SET_PLAYER_PREVIOUS_VARIATION_DATA(Player player, int ComponentNumber, int DrawableID, int AltDrawableID, int TextureID, int PaletteID);
```

```
Manually sets the previous variation data, restored when the parachute / scuba prop is removed as part of CTaskTakeOffPedVariation.

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
```
