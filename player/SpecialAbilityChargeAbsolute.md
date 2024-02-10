---
ns: PLAYER
aliases: ["0xb7b0870eb531d08d"]
---
## SPECIAL_ABILITY_CHARGE_ABSOLUTE

```c
// 0xB7B0870EB531D08D
void SPECIAL_ABILITY_CHARGE_ABSOLUTE(Player player, int charge, bool ignoreActive, int abilitySlot);
```

Adds an absolute charge in seconds to the player special ability meter. By default the ability meter is 30 seconds so adding a charge of 30 or higher will fill the meter.

