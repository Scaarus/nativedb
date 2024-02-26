---
ns: SOCIALCLUB
aliases: ["0xda024bdbd600f44a"]
---
## SC_INBOX_MESSAGE_PUSH_GAMER_T0_RECIP_LIST

```c
// 0xDA024BDBD600F44A
void SC_INBOX_MESSAGE_PUSH_GAMER_T0_RECIP_LIST(Any* hGamer);
```

Push this gamer into the recipient list used to send INBOX messages

Call this function a bunch of times to put together the list, then call an INBOX_SEND function. The list is cleared each time the list is used to send a message

