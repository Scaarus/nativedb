---
ns: SCRIPT
aliases: ["0xc5bc038960e9db27"]
---
## SET_SCRIPT_WITH_NAME_HASH_AS_NO_LONGER_NEEDED

```c
// 0xC5BC038960E9DB27
void SET_SCRIPT_WITH_NAME_HASH_AS_NO_LONGER_NEEDED(int hashOfScriptName);
```

Tell the code that this script can safely be removed from memory once there are no instances of it running. Does the same as SET_SCRIPT_AS_NO_LONGER_NEEDED but takes an integer containing the hash of the script name instead of the name as a string.

