---
ns: NETWORK
aliases: ["0xda7de67f5fe5ee13"]
---
## NETWORK_IS_SCRIPT_ACTIVE_BY_HASH

```c
// 0xDA7DE67F5FE5EE13
bool NETWORK_IS_SCRIPT_ACTIVE_BY_HASH(int scriptHash, int instanceId, bool localOnly, int positionHash);
```

Returns true if any scripts with the given hash are running locally or remotely on any other machine involved in the network game


## Parameters
* **scriptHash**: 
* **instanceId**: 
* **localOnly**: if set the command only checks if there are any local instances of the script running, there may not be a script thread running but the code that manages the thread may still be active cleaning up (Default value: `False`)
* **positionHash**: (Default value: `0`)
