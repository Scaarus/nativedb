---
ns: VEHICLE
aliases: ["0xa551be18c11a476d"]
---
## GET_NUM_MOD_COLORS

```c
// 0xA551BE18C11A476D
int GET_NUM_MOD_COLORS(int colorType, bool ase);
```

```
Returns the number of available color for a specific color type. More...

Possible values for colorType:
| Index | Name |
| --- | --- |
| 0 | Metallic |
| 277 | Classic |
| 278 | Pearlescent |
| 279 | Matte |
| 280 | Metals |
| 281 | Chrome |
| 282 | Chameleon |
| 283 | None If This Is Set, The Vehicle Doesn'T Use Mod Colors, It Uses The Regular Color System |


If base is false it willr eturn the index of the specular color index. This only applies for MCT_PEARLESCENT, the rest have only one index
```
