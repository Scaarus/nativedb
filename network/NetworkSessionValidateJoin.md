---
ns: NETWORK
aliases: ["0xc19f6c8e7865a6ff"]
---
## NETWORK_SESSION_VALIDATE_JOIN

```c
// 0xC19F6C8E7865A6FF
void NETWORK_SESSION_VALIDATE_JOIN(bool JoinSuccessful);
```

Functions to allow script to validate a join. These are used to allow join failure for conditions that may not be checked in code allowing us to re-enter the matchmaking flow. Call NETWORK_SESSION_SET_SCRIPT_VALIDATE_JOIN when script run condition checks after joining to enable.


## Parameters
* **JoinSuccessful**: Result of script checks on whether player can join the session.
