---
ns: PLAYER
aliases: ["0x2e7b9b683481687d"]
---
## SPECIAL_ABILITY_CHARGE_SMALL

```c
// 0x2E7B9B683481687D
void SPECIAL_ABILITY_CHARGE_SMALL(Player player, bool increment, bool ignoreActive, int abilitySlot);
```

Modifies the player special ability meter with a small charge. If increment is true it will add a charge other remove. If ignoreActive is true the charge will be added even if the ability is currently active otherwise command is ignored.

