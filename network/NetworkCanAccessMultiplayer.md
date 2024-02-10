---
ns: NETWORK
aliases: ["0xaf50da1a3f8b1ba4"]
---
## NETWORK_CAN_ACCESS_MULTIPLAYER

```c
// 0xAF50DA1A3F8B1BA4
bool NETWORK_CAN_ACCESS_MULTIPLAYER(int nAccessCode);
```

Return TRUE if the game can ACCESS multiplayer. Check this function once. If FALSE, fall out of MP. Must be called prior to: NETWORK_SESSION_ENTER NETWORK_SESSION_FRIEND_MATCHMAKING NETWORK_SESSION_SOCIAL_MATCHMAKING NETWORK_SESSION_CREW_MATCHMAKING NETWORK_SESSION_ACTIVITY_QUICKMATCH NETWORK_SESSION_HOST Code deal with NETWORK_SESSION_JOIN_INVITE

## nAccessCode Values:
| Value | Name |
| --- | --- |
| 34 | Granted |
| 35 | Denied Tunable Not Found |
| 36 | Denied Tunable False |
| 37 | Denied Network Locked |
| 38 | Denied Invalid Profile Settings |
| 39 | Denied Prologue Incomplete |
| 40 | Denied Not Signed In |
| 41 | Denied Not Signed Online |
| 42 | Denied No Online Privilege |
| 43 | Denied No Scs Credentials |
| 44 | Denied No Scs Privilege |
| 45 | Denied Multiplayer Disabled |
| 46 | Denied No Tunables |
| 47 | Denied No Background Script |

