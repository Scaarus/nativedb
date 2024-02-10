---
ns: NETWORK
aliases: ["0x3e9bb38102a589b0"]
---
## NETWORK_DO_TRANSITION_TO_GAME

```c
// 0x3E9BB38102A589B0
bool NETWORK_DO_TRANSITION_TO_GAME(bool WithPlayers, int nMaxPlayers);
```

This will transition back to freemode from a launched activity session. All players returning to freemode should call this (including a quit) bWithPlayers should only be used on session host and indicates that we'll inform the remaining players to come with us. Use when host hits 'continue' nMaxPlayers is used if we cannot find a match and need to host.

