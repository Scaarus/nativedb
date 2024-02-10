---
ns: PLAYER
aliases: ["0xed481732dff7e997"]
---
## SPECIAL_ABILITY_CHARGE_CONTINUOUS

```c
// 0xED481732DFF7E997
void SPECIAL_ABILITY_CHARGE_CONTINUOUS(Player player, bool ignoreActive, int abilitySlot);
```

Flags the continuous charge as active. This needs to be called every frame while charging should take place. If ignoreActive is true the charge will be added even if the ability is currently active otherwise command is ignored.

