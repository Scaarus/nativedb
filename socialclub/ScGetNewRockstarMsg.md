---
ns: SOCIALCLUB
aliases: ["0xdf649c4e9afdd788"]
---
## SC_GET_NEW_ROCKSTAR_MSG

```c
// 0xDF649C4E9AFDD788
string SC_GET_NEW_ROCKSTAR_MSG();
```

Retrieves the last new Rockstar Message sent via the SC Admin site. Note: This should only be called if SC_HAS_NEW_ROCKSTAR_MSG has returned TRUE Once this function is called, SC_HAS_NEW_ROCKSTAR_MSG will return FALSE until a new message is posted.

