---
ns: NETWORK
aliases: ["0x9e80a5ba8109f974"]
---
## NETWORK_DO_TRANSITION_TO_NEW_FREEMODE

```c
// 0x9E80A5BA8109F974
bool NETWORK_DO_TRANSITION_TO_NEW_FREEMODE(Any* hGamers, int nNumGamers, int nMaxPlayers, bool IsPrivate, bool AllowPreviousJoin, int nHostFlags);
```

This will transition back to freemode from a launched activity session. Like above but we immediately host a session.


## Parameters
* **hGamers**: 
* **nNumGamers**: 
* **nMaxPlayers**: 
* **IsPrivate**: 
* **AllowPreviousJoin**: (Default value: `True`)
* **nHostFlags**: (Default value: `0`)
