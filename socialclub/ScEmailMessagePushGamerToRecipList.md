---
ns: SOCIALCLUB
aliases: ["0x2330c12a7a605d16"]
---
## SC_EMAIL_MESSAGE_PUSH_GAMER_TO_RECIP_LIST

```c
// 0x2330C12A7A605D16
void SC_EMAIL_MESSAGE_PUSH_GAMER_TO_RECIP_LIST(Any* hGamer);
```

Push this gamer into the recipient list used to send email messages

Call this function a bunch of times to put together the list, then call an [`SC_EMAIL_SEND_EMAIL`](#_0x116FB94DC4B79F17) function. The list is cleared each time the list is used to send a message

