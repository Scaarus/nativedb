---
ns: STATS
aliases: ["0xe95c8a1875a02ca4"]
---
## PLAYSTATS_WEAPON_MODE_CHANGE

```c
// 0xE95C8A1875A02CA4
void PLAYSTATS_WEAPON_MODE_CHANGE(Hash weaponHash, Hash componentHash, Hash componentHash);
```

Metric set when the weapon mode changes. If the wepon is not changing a mod and just adding then set modeIdFrom to 0.

