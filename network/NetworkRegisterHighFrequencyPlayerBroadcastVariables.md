---
ns: NETWORK
aliases: ["0x55b917f38ca35331"]
---
## NETWORK_REGISTER_HIGH_FREQUENCY_PLAYER_BROADCAST_VARIABLES

```c
// 0x55B917F38CA35331
void NETWORK_REGISTER_HIGH_FREQUENCY_PLAYER_BROADCAST_VARIABLES(Any* Address, int Size, string DebugName);
```

Registers the variables for each player running the script This high frequency data will be updated every frame and send out updates as soon as possible. This feature is currently restricted to arrays of 20 script vars or less. Please only use this when strictly necessary!


## Parameters
* **Address**: 
* **Size**: 
* **DebugName**: (Default value: `Null`)
