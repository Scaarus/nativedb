---
ns: SOCIALCLUB
aliases: ["0x7572ef42fc6a9b6d"]
---
## SC_INBOX_MESSAGE_GET_DATA_STRING

```c
// 0x7572EF42FC6A9B6D
bool SC_INBOX_MESSAGE_GET_DATA_STRING(int msgIndex, Any* value);
```

Retrieve the given named value of the given type from the message at the given index.


## Parameters
* **msgIndex**: index of the message in the inbox
* **value**: The value of the variables if found and set
