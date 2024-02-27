---
ns: NETWORK
aliases: ["0x2b297170e982e21e"]
---
## NETWORK_REGISTER_HIGH_FREQUENCY_HOST_BROADCAST_VARIABLES

```c
// 0x2B297170E982E21E
void NETWORK_REGISTER_HIGH_FREQUENCY_HOST_BROADCAST_VARIABLES(Any* Address, int Size, string DebugName);
```

Registers the variables that the host alters and that the clients need to be updated on. This high frequency data will be updated every frame and send out updates as soon as possible. This feature is currently restricted to arrays of 20 script vars or less. Please only use this when strictly necessary!


## Parameters
* **Address**: 
* **Size**: 
* **DebugName**: (Default value: `Null`)
