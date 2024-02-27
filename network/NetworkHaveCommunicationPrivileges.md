---
ns: NETWORK
aliases: ["0xaeef48cdf5b6ce7c"]
---
## NETWORK_HAVE_COMMUNICATION_PRIVILEGES

```c
// 0xAEEF48CDF5B6CE7C
bool NETWORK_HAVE_COMMUNICATION_PRIVILEGES(int nPrivilegeType, int PlayerIndex);
```

Returns true if the player has communication / voicechat privileges.

## nPrivilegeType Values:
| Value | Name |
| --- | --- |
| 0 | Everyone |
| 1 | Friends |


Privilege Check Type (One of PRIVILEGE_CHECK)


## Parameters
* **nPrivilegeType**: (Default value: `Everyone`)
* **PlayerIndex**: 
