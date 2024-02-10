---
ns: NETWORK
aliases: ["0x6f3d4ed9bee4e61d"]
---
## NETWORK_SESSION_HOST

```c
// 0x6F3D4ED9BEE4E61D
bool NETWORK_SESSION_HOST(int nGameMode, int nMaxPlayers, bool IsPrivate);
```

```
Hosts a session
```

## Parameters
* **nGameMode**: Gamemode value from script enum
* **nMaxPlayers**: Max players that can join this session, including local player
* **IsPrivate**: If this session is private (closed) or not
