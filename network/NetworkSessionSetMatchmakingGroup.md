---
ns: NETWORK
aliases: ["0x49ec8030f5015f8b"]
---
## NETWORK_SESSION_SET_MATCHMAKING_GROUP

```c
// 0x49EC8030F5015F8B
void NETWORK_SESSION_SET_MATCHMAKING_GROUP(int nGroup);
```

```
Functions to allow script to set the matchmaking group for the local player and the maximum number of players in each group

Possible values for nGroup:
| Index | Name |
| --- | --- |
| 64 | Freemoder |
| 65 | Cop |
| 66 | Vagos |
| 67 | Lost |
| 68 | Sctv |
```

## Parameters
* **nGroup**: One of MATCHMAKING_GROUP
