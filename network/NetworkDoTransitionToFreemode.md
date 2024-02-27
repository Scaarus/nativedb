---
ns: NETWORK
aliases: ["0x3aad8b2fca1e289f"]
---
## NETWORK_DO_TRANSITION_TO_FREEMODE

```c
// 0x3AAD8B2FCA1E289F
bool NETWORK_DO_TRANSITION_TO_FREEMODE(Any* hGamers, int nNumGamers, bool SocialMatchmaking, int nMaxPlayers, int nMmFlags);
```

This will transition back to freemode from a launched activity session. All players returning to freemode should call this (including a quit) This takes an array of gamer handles of players that we should take with us. Specify 0 for nNumGamers to quit back solo nMaxPlayers is used if we cannot find a match and need to host.


## Parameters
* **hGamers**: 
* **nNumGamers**: 
* **SocialMatchmaking**: 
* **nMaxPlayers**: 
* **nMmFlags**: (Default value: `0`)
