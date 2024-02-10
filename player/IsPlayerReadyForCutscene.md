---
ns: PLAYER
aliases: ["0x908cbecc2caa3690"]
---
## IS_PLAYER_READY_FOR_CUTSCENE

```c
// 0x908CBECC2CAA3690
bool IS_PLAYER_READY_FOR_CUTSCENE();
```

Returns if the player is in a safe state to trigger a cutscene.

the player is considered safe if they are: In a car and not entering or exiting or On foot and not ragdolling Use CAN_PLAYER_START_CUTSCENE() - this calls the above function, but also checks that the player is not a passenger in a taxi.

