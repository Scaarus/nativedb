---
ns: LOBBY
aliases: ["0xfa1e0e893d915215"]
---
## SHUTDOWN_SESSION_CLEARS_AUTO_MULTIPLAYER

```c
// 0xFA1E0E893D915215
void SHUTDOWN_SESSION_CLEARS_AUTO_MULTIPLAYER(bool ClearsAutoMultiplayer);
```

Call this with FALSE to allow you to call [LOBBY_SET_AUTO_MULTIPLAYER](#_0xB0C56BD3D808D863)(TRUE) and keep that TRUE flag across one session shutdown

