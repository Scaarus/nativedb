---
ns: NETWORK
aliases: ["0x07eab372c8841d99"]
---
## NETWORK_CHECK_TEXT_COMMUNICATION_PRIVILEGES

```c
// 0x07EAB372C8841D99
bool NETWORK_CHECK_TEXT_COMMUNICATION_PRIVILEGES(int nPrivilegeType, int nGamerIndex, bool CheckHasPrivilege);
```

As above, but allows check using a particular gamer index Use GAMER_INDEX_ANYONE to check any player. You can check if any player does NOT have the privilege by setting bCheckHasPrivilege to FALSE

## nPrivilegeType Values:
| Value | Name |
| --- | --- |
| 0 | Everyone |
| 1 | Friends |


## Parameters
* **nPrivilegeType**: (Default value: `Everyone`)
* **nGamerIndex**: (Default value: `Gamer_Index_Local`)
* **CheckHasPrivilege**: (Default value: `True`)
