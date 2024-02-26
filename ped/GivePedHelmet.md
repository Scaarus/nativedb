---
ns: PED
aliases: ["0x54c7c4a94367717e"]
---
## GIVE_PED_HELMET

```c
// 0x54C7C4A94367717E
void GIVE_PED_HELMET(Ped ped, bool DontTakeOffHelmet, int HelmetPropFlag, int OverwriteHelmetTexId);
```

Give the ped a helmet

## HelmetPropFlag Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Bulky |
| 2 | Job (1<<1,) |
| 3 | Sunny (1<<2,) |
| 4 | Wet (1<<3,) |
| 5 | Cold (1<<4,) |
| 6 | Not In Car (1<<5,) |
| 7 | Bike Only (1<<6,) |
| 8 | Not Indoors (1<<7,) |
| 9 | Fire Retardent (1<<8,) |
| 10 | Armoured (1<<9,) |
| 11 | Lightly Armoured (1<<10,) |
| 12 | High Detail (1<<11,) |
| 13 | Default Helmet (1<<12,) |
| 14 | Random Helmet (1<<13,) |
| 15 | Script Helmet (1<<14,) |
| 32768 | Flight Helmet |
| 65536 | Hide In First Person |
| 131072 | Use Physics Hat 2 |
| 262144 | Pilot Helmet |

