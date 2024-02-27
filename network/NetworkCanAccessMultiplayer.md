---
ns: NETWORK
aliases: ["0xaf50da1a3f8b1ba4"]
---
## NETWORK_CAN_ACCESS_MULTIPLAYER

```c
// 0xAF50DA1A3F8B1BA4
bool NETWORK_CAN_ACCESS_MULTIPLAYER(int nAccessCode);
```

Return TRUE if the game can ACCESS multiplayer. Check this function once. If FALSE, fall out of MP. Must be called prior to: NETWORK_SESSION_ENTER NETWORK_SESSION_FRIEND_MATCHMAKING NETWORK_SESSION_SOCIAL_MATCHMAKING NETWORK_SESSION_CREW_MATCHMAKING NETWORK_SESSION_ACTIVITY_QUICKMATCH [`NETWORK_SESSION_HOST`](#_0x6F3D4ED9BEE4E61D) Code deal with [`NETWORK_SESSION_JOIN_INVITE`](#_0xC6F8AB8A4189CF3A)

## Values for `nAccessCode`:
| Value | Name |
| --- | --- |
| 0 | Granted |
| 1 | Denied Tunable Not Found |
| 2 | Denied Tunable False |
| 3 | Denied Network Locked |
| 4 | Denied Invalid Profile Settings |
| 5 | Denied Prologue Incomplete |
| 6 | Denied Not Signed In |
| 7 | Denied Not Signed Online |
| 8 | Denied No Online Privilege |
| 9 | Denied No Scs Credentials |
| 10 | Denied No Scs Privilege |
| 11 | Denied Multiplayer Disabled |
| 12 | Denied No Tunables |
| 13 | Denied No Background Script |

