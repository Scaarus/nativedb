---
ns: NETWORK
aliases: ["0x421e34c55f125964"]
---
## NETWORK_CAN_RECEIVE_LOCAL_INVITE

```c
// 0x421E34C55F125964
bool NETWORK_CAN_RECEIVE_LOCAL_INVITE(Any* hGamer);
```

Permission checks with a gamer handle Target gamer handle must be in a session with the local gamer (freeroam or corona) Can check if we have data for this player using NETWORK_PERMISSIONS_HAS_GAMER_RECORD

