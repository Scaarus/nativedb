---
ns: PLAYER
aliases: ["0xf113e3aa9bc54613"]
---
## SPECIAL_ABILITY_CHARGE_MEDIUM

```c
// 0xF113E3AA9BC54613
void SPECIAL_ABILITY_CHARGE_MEDIUM(Player player, bool increment, bool ignoreActive, int abilitySlot);
```

Modifies the player special ability meter with a medium charge. If increment is true it will add a charge other remove. If ignoreActive is true the charge will be added even if the ability is currently active otherwise command is ignored.


## Parameters
* **player**: 
* **increment**: 
* **ignoreActive**: 
* **abilitySlot**: (Default value: `0`)
