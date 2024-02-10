---
ns: PLAYER
aliases: ["0x5063f92f07c2a316"]
---
## GET_TIME_SINCE_LAST_ARREST

```c
// 0x5063F92F07C2A316
int GET_TIME_SINCE_LAST_ARREST();
```

Returns the time in milliseconds since the player was arrested and got respawned outside a police station.

Returns -1 if the player hasn't been arrested yet since starting a session.

