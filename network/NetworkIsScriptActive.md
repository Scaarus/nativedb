---
ns: NETWORK
aliases: ["0x9d40df90fad26098"]
---
## NETWORK_IS_SCRIPT_ACTIVE

```c
// 0x9D40DF90FAD26098
bool NETWORK_IS_SCRIPT_ACTIVE(string scriptName, int instanceId, bool localOnly, int positionHash);
```

```
Returns true if any scripts with the given name are running locally or remotely on any other machine involved in the network game
```

## Parameters
* **scriptName**: 
* **instanceId**: 
* **localOnly**: if set the command only checks if there are any local instances of the script running, there may not be a script thread running but the code that manages the thread may still be active cleaning up
* **positionHash**: 
