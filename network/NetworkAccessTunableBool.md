---
ns: NETWORK
aliases: ["0xaa6a47a573abb75a"]
---
## NETWORK_ACCESS_TUNABLE_BOOL

```c
// 0xAA6A47A573ABB75A
bool NETWORK_ACCESS_TUNABLE_BOOL(string szContext, string szTunableName);
```

Retrieves the tunable (szTunableName) in context (szContext) For FLOAT and INT, the value will be stored in the nTunable fTunable variables. The return value indicates whether the variable exists. We cannot pass bools by references so the bool value is just returned. Use NETWORK_DOES_TUNABLE_EXIST if you want to check if a BOOL tunable exists.

