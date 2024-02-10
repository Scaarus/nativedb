---
ns: NETWORK
aliases: ["0xa02e59562d711006"]
---
## NETWORK_SESSION_END

```c
// 0xA02E59562D711006
bool NETWORK_SESSION_END(bool ReturnToLobby, bool Blacklist);
```

```
Ends a network session
```

## Parameters
* **ReturnToLobby**: FALSE to leave this session, TRUE to remain (and return to the lobby state)
* **Blacklist**: Blacklist this session for 5 minutes, it will not be used for matchmaking (unless there are no other sessions)
