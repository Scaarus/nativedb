---
ns: PLAYER
aliases: ["0x74556e1420867eca"]
---
## IS_PLAYER_LOGGING_IN_NP

```c
// 0x74556E1420867ECA
bool IS_PLAYER_LOGGING_IN_NP();
```

Returns true if the player is logging in to Sony NP.

If this returns true,IS_PLAYER_ONLINE_NP() will return false because, although the player is logged in, he's not fully connected to all necessary back end services, and therefore not online.

