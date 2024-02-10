---
ns: PLAYER
aliases: ["0xfac75988a7d078d3"]
---
## SET_LAW_PEDS_CAN_ATTACK_NON_WANTED_PLAYER_THIS_FRAME

```c
// 0xFAC75988A7D078D3
void SET_LAW_PEDS_CAN_ATTACK_NON_WANTED_PLAYER_THIS_FRAME(Player player);
```

```
Allows law peds to attack player even if they have no wanted level. Essentially acts like a global "PCF_CanAttackNonWantedPlayerAsLaw" flag on all law peds. Must be called every frame to maintain effect.
```
