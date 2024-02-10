---
ns: SECURITY
aliases: ["0x40eb1efd921822bc"]
---
## REGISTER_SCRIPT_VARIABLE

```c
// 0x40EB1EFD921822BC
void REGISTER_SCRIPT_VARIABLE(int scriptVariable);
```

Register a script variable for protection with RageSec plugin. The plugin will keep an obfuscated shadow copy of the variable. Call this function whenever the protected script variable is modified to update the shadow copy at the plugin. Failing to do so will cause the plugin to think the script variable is being tampered with.

