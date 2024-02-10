---
ns: NETWORK
aliases: ["0xfb680d403909dc70"]
---
## NETWORK_ALLOW_GANG_TO_JOIN_TUTORIAL_SESSION

```c
// 0xFB680D403909DC70
void NETWORK_ALLOW_GANG_TO_JOIN_TUTORIAL_SESSION(int iTeam, int iInstanceID);
```

Puts the local player in a gang tutorial session - they will remain connected to other players in the session, but will be unable to interact with any players that have not called this command with the same iTeam value. Any locally controlled ambient population will be removed when this command is called, so ensure the player is placed where this will not be noticeable.


## Parameters
* **iTeam**: Multiple gangs may want to be in tutorial sessions at the same time, so the team ID is necessary to distinguish between these sessions
* **iInstanceID**: Script determined instance ID, allows a larger number of gang players to be split into multiple tutorial sessions
