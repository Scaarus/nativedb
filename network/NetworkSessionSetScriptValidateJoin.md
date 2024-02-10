---
ns: NETWORK
aliases: ["0x1153fa02a659051c"]
---
## NETWORK_SESSION_SET_SCRIPT_VALIDATE_JOIN

```c
// 0x1153FA02A659051C
void NETWORK_SESSION_SET_SCRIPT_VALIDATE_JOIN();
```

Functions to allow script to validate a join. These are used to allow join failure for conditions that may not be checked in code allowing us to re-enter the matchmaking flow. Call NETWORK_SESSION_SET_SCRIPT_VALIDATE_JOIN when script run condition checks after joining to enable.

