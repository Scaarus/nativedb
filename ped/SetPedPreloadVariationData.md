---
ns: PED
aliases: ["0x39d55a620fcb6a3a"]
---
## SET_PED_PRELOAD_VARIATION_DATA

```c
// 0x39D55A620FCB6A3A
int SET_PED_PRELOAD_VARIATION_DATA(Ped ped, int ComponentID, int DrawableID, int TextureID);
```

Sets a component variation to preload into memory, without applying it on the ped

## Values for `ComponentID`:
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

