---
ns: PED
aliases: ["0xc0e78d5c2ce3eb25"]
---
## SET_PED_HELMET_FLAG

```c
// 0xC0E78D5C2CE3EB25
void SET_PED_HELMET_FLAG(Ped ped, int HelmetPropFlag);
```

Sets the helmet flag for which tpye of prop to use

## Values for `HelmetPropFlag`:
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


## Parameters
* **ped**: 
* **HelmetPropFlag**: (Default value: `Pv_Flag_Default_Helmet`)
