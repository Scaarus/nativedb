---
ns: PED
aliases: ["0x497bf74a7b9cb952"]
---
## SET_PED_HEAD_OVERLAY_TINT

```c
// 0x497BF74A7B9CB952
void SET_PED_HEAD_OVERLAY_TINT(Ped ped, int slot, int rampType, int tint, int tint2);
```

```
Sets the tint index for the specified head blend overlay slot

Possible values for slot:
| Index | Name |
| --- | --- |
| 0 | Blemishes |
| 1 | Facial Hair |
| 2 | Eyebrow |
| 3 | Aging |
| 4 | Makeup |
| 5 | Blusher |
| 6 | Damage |
| 7 | Base Detail |
| 8 | Skin Detail 1 |
| 9 | Skin Detail 2 |
| 10 | Body 1 |
| 11 | Body 2 |
| 12 | Body 3 |


Possible values for rampType:
| Index | Name |
| --- | --- |
| 0 | None |
| 32 | Hair |
| 33 | Makeup |
```
