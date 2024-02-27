---
ns: PLAYER
aliases: ["0x7bae68775557ae0b"]
---
## SET_PLAYER_PREVIOUS_VARIATION_DATA

```c
// 0x7BAE68775557AE0B
void SET_PLAYER_PREVIOUS_VARIATION_DATA(Player player, int ComponentNumber, int DrawableID, int AltDrawableID, int TextureID, int PaletteID);
```

Manually sets the previous variation data, restored when the parachute / scuba prop is removed as part of CTaskTakeOffPedVariation.

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


## Parameters
* **player**: 
* **ComponentNumber**: 
* **DrawableID**: 
* **AltDrawableID**: (Default value: `0`)
* **TextureID**: (Default value: `0`)
* **PaletteID**: (Default value: `0`)
