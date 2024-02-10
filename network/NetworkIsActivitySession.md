---
ns: NETWORK
aliases: ["0x05095437424397fa"]
---
## NETWORK_IS_ACTIVITY_SESSION

```c
// 0x05095437424397FA
bool NETWORK_IS_ACTIVITY_SESSION();
```

```
These check the current setup of the main session. The main session will still be marked as an activity session after launching via transition, This is so that matchmaking can still distinguish between a general freemode session and a transition launched session. Check if it's an activity via NETWORK_IS_ACTIVITY_SESSION and change back to freemode using NETWORK_MARK_AS_GAME_SESSION
```
