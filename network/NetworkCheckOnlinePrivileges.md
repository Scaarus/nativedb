---
ns: NETWORK
aliases: ["0x78321bea235fd8cd"]
---
## NETWORK_CHECK_ONLINE_PRIVILEGES

```c
// 0x78321BEA235FD8CD
bool NETWORK_CHECK_ONLINE_PRIVILEGES(int nGamerIndex, bool CheckHasPrivilege);
```

As above, but allows check using a particular gamer index Use GAMER_INDEX_ANYONE to check any player. You can check if any player does NOT have the privilege by setting bCheckHasPrivilege to FALSE

