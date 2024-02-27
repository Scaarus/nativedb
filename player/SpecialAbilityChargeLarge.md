---
ns: PLAYER
aliases: ["0xf733f45fa4497d93"]
---
## SPECIAL_ABILITY_CHARGE_LARGE

```c
// 0xF733F45FA4497D93
void SPECIAL_ABILITY_CHARGE_LARGE(Player player, bool increment, bool ignoreActive, int abilitySlot);
```

Modifies the player special ability meter with a large charge. If increment is true it will add a charge other remove. If ignoreActive is true the charge will be added even if the ability is currently active otherwise command is ignored.


## Parameters
* **player**: 
* **increment**: 
* **ignoreActive**: 
* **abilitySlot**: (Default value: `0`)
