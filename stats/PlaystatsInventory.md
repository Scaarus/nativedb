---
ns: STATS
aliases: ["0x887dad63cf5b7908"]
---
## PLAYSTATS_INVENTORY

```c
// 0x887DAD63CF5B7908
void PLAYSTATS_INVENTORY(Any* data);
```

Triggers after a snack or armor item type are added to the inventory, removed from the inventory, or consumed outwith the inventory (vending machines, bars etc.). Would trigger each time the item type changes, or after X seconds from the change (set by tunable) that allows for the case where the player hits "buy", "drop" or "use" repeatedly.

