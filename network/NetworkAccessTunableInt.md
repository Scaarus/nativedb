---
ns: NETWORK
aliases: ["0x8be1146dfd5d4468"]
---
## NETWORK_ACCESS_TUNABLE_INT

```c
// 0x8BE1146DFD5D4468
bool NETWORK_ACCESS_TUNABLE_INT(string szContext, string szTunableName);
```

Retrieves the tunable (szTunableName) in context (szContext) For FLOAT and INT, the value will be stored in the nTunable fTunable variables. The return value indicates whether the variable exists. We cannot pass bools by references so the bool value is just returned. Use NETWORK_DOES_TUNABLE_EXIST if you want to check if a BOOL tunable exists.

