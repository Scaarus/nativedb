---
ns: NETWORK
aliases: ["0xd66c9e72b3cc4982"]
---
## NETWORK_DISPLAYNAMES_FROM_HANDLES_START

```c
// 0xD66C9E72B3CC4982
int NETWORK_DISPLAYNAMES_FROM_HANDLES_START(gamer_handle gamerHandles, int count);
```

PURPOSE Queues up a request to get a list of display names given a list of gamerHandles (async). Returns a requestId which is passed to NETWORK_GET_DISPLAYNAMES_FROM_HANDLES (see below). If the returned value is < 0, an error has occured and the requestId is not valid.

