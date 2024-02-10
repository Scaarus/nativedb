---
ns: NETWORK
aliases: ["0x5ed0356a0ce3a34f"]
---
## NETWORK_GET_TIMEOUT_TIME

```c
// 0x5ED0356A0CE3A34F
int NETWORK_GET_TIMEOUT_TIME();
```

Returns the time in seconds that the code will wait for an unresponding player before disconnecting them. If -notimeouts is being used, this will return 0.

