---
ns: PED
aliases: ["0xc0e78d5c2ce3eb25"]
---
## SET_PED_HELMET_FLAG

```c
// 0xC0E78D5C2CE3EB25
void SET_PED_HELMET_FLAG(Ped ped, int HelmetPropFlag);
```

```
Sets the helmet flag for which tpye of prop to use

Possible values for HelmetPropFlag:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Bulky |
| 235 | Job 1<<1, |
| 236 | Sunny 1<<2, |
| 237 | Wet 1<<3, |
| 238 | Cold 1<<4, |
| 239 | Not In Car 1<<5, |
| 240 | Bike Only 1<<6, |
| 241 | Not Indoors 1<<7, |
| 242 | Fire Retardent 1<<8, |
| 243 | Armoured 1<<9, |
| 244 | Lightly Armoured 1<<10, |
| 245 | High Detail 1<<11, |
| 246 | Default Helmet 1<<12, |
| 247 | Random Helmet 1<<13, |
| 248 | Script Helmet 1<<14, |
| 32768 | Flight Helmet |
| 65536 | Hide In First Person |
| 131072 | Use Physics Hat 2 |
| 262144 | Pilot Helmet |
```
