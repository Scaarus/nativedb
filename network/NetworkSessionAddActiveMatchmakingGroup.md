---
ns: NETWORK
aliases: ["0xcae55f48d3d7875c"]
---
## NETWORK_SESSION_ADD_ACTIVE_MATCHMAKING_GROUP

```c
// 0xCAE55F48D3D7875C
void NETWORK_SESSION_ADD_ACTIVE_MATCHMAKING_GROUP(int nGroup);
```

Functions to allow script to set the matchmaking group for the local player and the maximum number of players in each group

## Values for `nGroup`:
| Value | Name |
| --- | --- |
| 0 | Freemoder |
| 1 | Cop |
| 2 | Vagos |
| 3 | Lost |
| 4 | Sctv |


## Parameters
* **nGroup**: One of MATCHMAKING_GROUP
