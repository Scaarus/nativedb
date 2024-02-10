---
ns: VEHICLE
aliases: ["0x2b5f9d2af1f1722d"]
---
## SET_VEHICLE_HAS_BEEN_OWNED_BY_PLAYER

```c
// 0x2B5F9D2AF1F1722D
void SET_VEHICLE_HAS_BEEN_OWNED_BY_PLAYER(Vehicle vehicle, bool NewVal);
```

Sets a vehicle owned by the player so he wont get a wanted level when entering it.

f vehicle has not been owned by player, the player will get a wanted level when entering (if spotted by police). If the player has already owned a vehicle he is free to use it. (The game will set this flag to true first time the player drives a vehicle) Mission vehicles will default to true

