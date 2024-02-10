---
ns: SCRIPT
aliases: ["0x5f0f0c783eb16c04"]
---
## HAS_SCRIPT_WITH_NAME_HASH_LOADED

```c
// 0x5F0F0C783EB16C04
bool HAS_SCRIPT_WITH_NAME_HASH_LOADED(int hashOfScriptName);
```

Returns TRUE if the script program is in memory. Does the same as HAS_SCRIPT_LOADED but takes an integer containing the hash of the script name instead of the name as a string.

