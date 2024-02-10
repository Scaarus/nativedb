---
ns: SOCIALCLUB
aliases: ["0x2c015348cf19ca1d"]
---
## SC_INBOX_SET_MESSAGE_AS_READ_AT_INDEX

```c
// 0x2C015348CF19CA1D
bool SC_INBOX_SET_MESSAGE_AS_READ_AT_INDEX(int msgIndex);
```

```
Marks the inbox message at the given index a LOCALLY read...as a way to locally mark that the message has been processed. Next time the inbox is locally cleaned, the read messages are purged.
```
