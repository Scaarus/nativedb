---
ns: NETWORK
aliases: ["0x9d724b400a7e8ffc"]
---
## SET_NETWORK_ID_CAN_BE_REASSIGNED

```c
// 0x9D724B400A7E8FFC
void SET_NETWORK_ID_CAN_BE_REASSIGNED(Network network, bool CanBeReassigned);
```

```
Sets whether this script object can be reassigned to other machines if the owning player leaves the session. If you are disabling reassignment for an object you should prevent it migrating to other machine normally via calling SET_NETWORK_ID_CAN_MIGRATE(FALSE) first.
```
