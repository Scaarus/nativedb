---
ns: NETWORK
aliases: ["0x42b2daa6b596f5f8"]
---
## NETWORK_GET_ENTITY_KILLER_OF_PLAYER

```c
// 0x42B2DAA6B596F5F8
Entity NETWORK_GET_ENTITY_KILLER_OF_PLAYER(Player player, Hash weaponHash);
```

Returns the Entity that has killed the other player last.
So you can use these commands on that entity: - IS_ENTITY_A_PED() - IS_ENTITY_A_VEHICLE() And if the entity is a ped you can convert ENTITY_INDEX to PED_INDEX and find if its a player or not: - IS_PED_A_PLAYER()

-1 means the killer is unknown

