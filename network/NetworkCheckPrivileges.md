---
ns: NETWORK
aliases: ["0x0cf6cc51aa18f0f8"]
---
## NETWORK_CHECK_PRIVILEGES

```c
// 0x0CF6CC51AA18F0F8
bool NETWORK_CHECK_PRIVILEGES(int nLocalGamerIndex, int nPrivilegeTypeBitfield, bool AttempResolution);
```

```
Begin a check through the platform API to see if the specified local user has the specified privileges set.
```

## Parameters
* **nLocalGamerIndex**: Index of the local gamer we want to check privileges for
* **nPrivilegeTypeBitfield**: Bitfield of privilege types to check. See bit definitions above (i.e. PRIVILEGE_TYPE_DURANGO_ADD_FRIEND)
* **AttempResolution**: Whether the system should be allowed to acquire a privilege for the user. When true, the system may prompt the user to upgrade their account. (i.e. prompt to upgrade to Xbox LIVE Gold)
