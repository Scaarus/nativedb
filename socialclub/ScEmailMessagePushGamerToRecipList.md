---
ns: SOCIALCLUB
aliases: ["0x2330c12a7a605d16"]
---
## SC_EMAIL_MESSAGE_PUSH_GAMER_TO_RECIP_LIST

```c
// 0x2330C12A7A605D16
void SC_EMAIL_MESSAGE_PUSH_GAMER_TO_RECIP_LIST(gamer_handle hGamer);
```

Push this gamer into the recipient list used to send email messages NOTE: Call this function a bunch of times to put together the list, then call an SC_EMAIL_SEND_EMAIL function. The list is cleared each time the list is used to send a message

