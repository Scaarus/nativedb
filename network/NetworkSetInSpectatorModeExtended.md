---
ns: NETWORK
aliases: ["0x419594e137637120"]
---
## NETWORK_SET_IN_SPECTATOR_MODE_EXTENDED

```c
// 0x419594E137637120
void NETWORK_SET_IN_SPECTATOR_MODE_EXTENDED(bool InSpectatorMode, Ped ped, bool skipTutorialCheck);
```

Set the local in spectator Mode. pedIndex - Ped index to spectate. If the index is -1 the it only sets the spectator flag. By default it's not allowed to start spectating a player in a different tutorial session, this can be allowed by setting the skipTutorialCheck parameter

