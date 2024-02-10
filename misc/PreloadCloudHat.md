---
ns: MISC
aliases: ["0x11b56fbbf7224868"]
---
## PRELOAD_CLOUD_HAT

```c
// 0x11B56FBBF7224868
void PRELOAD_CLOUD_HAT(string CloudHatName);
```

forces a cloud hat to stream into memory,even though we are not necesarrily transitioning to it yet (for transitioning to instantly in special cutscenes)
the cloudhat will be released from memory when it either transitions out normaly after use, or RELEASE_PRELOAD_CLOUD_HAT() is called


## Parameters
* **CloudHatName**: Preload cloud hat into memory,
