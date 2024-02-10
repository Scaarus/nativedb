---
ns: NETWORK
aliases: ["0x58cc181719256197"]
---
## NETWORK_GET_DISPLAYNAMES_FROM_HANDLES

```c
// 0x58CC181719256197
int NETWORK_GET_DISPLAYNAMES_FROM_HANDLES(int requestId, text_label_63 displayNames, int count);
```

PURPOSE Takes a requestId issued by NETWORK_DISPLAYNAMES_FROM_HANDLES_START. Returns an error code (-1=failed, 0=succeeded, 1=pending). Upon succeeding, displayNames is populated. If pending is returned, then the request is still retrieving display names. The requestId is no longer valid after this function returns succeeded or failed (the request is considered completed and is added back to the request pool so it can be reused).

