---
ns: PLAYER
aliases: ["0xd9284a8c0d48352c"]
---
## SET_PLAYER_PARACHUTE_VARIATION_OVERRIDE

```c
// 0xD9284A8C0D48352C
void SET_PLAYER_PARACHUTE_VARIATION_OVERRIDE(Player player, int ComponentNumber, int NewDrawableNumber, int TexID, int AltDrawableID);
```

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


An override for parachute variation. Used to sync up script and code.


## Parameters
* **player**: 
* **ComponentNumber**: 
* **NewDrawableNumber**: 
* **TexID**: (Default value: `0`)
* **AltDrawableID**: (Default value: `0`)
