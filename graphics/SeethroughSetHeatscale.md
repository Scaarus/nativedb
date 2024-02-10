---
ns: GRAPHICS
aliases: ["0xd7d0b00177485411"]
---
## SEETHROUGH_SET_HEATSCALE

```c
// 0xD7D0B00177485411
void SEETHROUGH_SET_HEATSCALE(int type, float param);
```

```
SeeThrough Effect : Set the amount of heat emitted for a thermal type.

Possible values for type:
| Index | Name |
| --- | --- |
| 0 | Dead |
| 1 | Cold |
| 2 | Warm |
| 3 | Hot |


scale goes from 0 (cold) to 1 (hot)
```
