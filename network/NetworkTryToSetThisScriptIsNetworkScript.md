---
ns: NETWORK
aliases: ["0xd1110739eeadb592"]
---
## NETWORK_TRY_TO_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT

```c
// 0xD1110739EEADB592
bool NETWORK_TRY_TO_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT(int MaxNumPlayers, bool activeInSinglePlayer, int InstanceId);
```

Works in the same way as NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT but returns FALSE if it fails. An example of a reason for failing would be if the command is called for an object brain and there is already a networked object brain at the same coordinates.

