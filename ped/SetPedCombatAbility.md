---
ns: PED
aliases: ["0xc7622c0d36b2fda8"]
---
## SET_PED_COMBAT_ABILITY

```c
// 0xC7622C0D36B2FDA8
void SET_PED_COMBAT_ABILITY(Ped ped, int PedCombatAbilityType);
```

Set the peds combat level.

## Values for `PedCombatAbilityType`:
| Value | Name |
| --- | --- |
| 0 | Poor (Ped Has Low Combat Ability) |
| 1 | Average (Ped Has Average Combat Ability) |
| 2 | Professional (Ped Has High Combat Ability) |


COMBAT_ABILITY_LEVEL are in commands_ped.sch

Combat ability is how quickly the ped responds in combat.

