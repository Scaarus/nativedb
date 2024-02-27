---
ns: NETWORK
aliases: ["0x34f9e9049454a7a0"]
---
## NETWORK_BLOCK_INVITES

```c
// 0x34F9E9049454A7A0
void NETWORK_BLOCK_INVITES(bool Blocked);
```

Use this to block invites from being actioned. This keeps the invite around. An EVENT_NETWORK_INVITE_ACCEPTED still fires. Script must call [`NETWORK_SESSION_CANCEL_INVITE`](#_0x2FBF47B1B36D36F9) if we do not want to action the invite. Reset to unblocked when no longer required

