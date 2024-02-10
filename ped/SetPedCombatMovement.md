---
ns: PED
aliases: ["0x4d9ca1009afbd057"]
---
## SET_PED_COMBAT_MOVEMENT

```c
// 0x4D9CA1009AFBD057
void SET_PED_COMBAT_MOVEMENT(Ped ped, int PedCombatMoveType);
```

Set the peds movment type during combat.

## PedCombatMoveType Values:
| Value | Name |
| --- | --- |
| 193 | Stationary Stands Totally Still During Combat |
| 194 | Defensive Seeks A Defensive Position. |
| 195 | Willadvance Will Advance Forward In Combat |
| 196 | Willretreat Will Retreat If The Enemy Gets Too Close |


COMBAT_MOVEMENT are in commands_ped.sch

