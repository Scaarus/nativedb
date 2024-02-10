---
ns: NETWORK
aliases: ["0x1ca59e306ecb80a5"]
---
## NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT

```c
// 0x1CA59E306ECB80A5
void NETWORK_SET_THIS_SCRIPT_IS_NETWORK_SCRIPT(int MaxNumPlayers, bool activeInSinglePlayer, int InstanceId);
```

This must be called if the script is to be networked, before you register the broadcast data. MaxNumPlayers - The maximum number of players who can participate in the script InstanceId - An id that can be assigned to the script to distinguish it from other scripts of the same type running at the same time

