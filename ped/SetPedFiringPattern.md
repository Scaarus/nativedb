---
ns: PED
aliases: ["0x9ac577f5a12ad8a9"]
---
## SET_PED_FIRING_PATTERN

```c
// 0x9AC577F5A12AD8A9
void SET_PED_FIRING_PATTERN(Ped ped, int FiringPatternHash);
```

Sets the peds default firing pattern (some tasks will over write this due to specific behaviors like blind fire)

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| -1857128337 | Burst Fire Heli |
| -1842093953 | Tampa Mortar |
| -957453492 | Full Auto |
| -753768974 | Burst Fire Driveby |
| -687903391 | Burst Fire |
| -490063247 | Slow Fire Tank |
| 445831135 | Short Bursts |
| 1122960381 | Burst Fire Micro |
| 1566631136 | Single Shot |
| 2055493265 | Delay Fire By One Sec |


Needs a vlid firing pattern hash, will assert with an invalid one

