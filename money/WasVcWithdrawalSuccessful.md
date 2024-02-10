---
ns: MONEY
aliases: ["0x6fcf8ddea146c45b"]
---
## WAS_VC_WITHDRAWAL_SUCCESSFUL

```c
// 0x6FCF8DDEA146C45B
bool WAS_VC_WITHDRAWAL_SUCCESSFUL();
```

Query whether a VC transfer was successful. Take as a parameter a transfer ID returned by TRANSFER_VC WARNING: Will return false until HAS_VC_TRANSFER_COMPLETED is returning true, so be sure to check HAS_VC_TRANSFER_COMPLETED first.

