---
ns: GRAPHICS
aliases: ["0xbaabbb23eb6e484e"]
---
## SET_TV_CHANNEL

```c
// 0xBAABBB23EB6E484E
void SET_TV_CHANNEL(int iChannel);
```

turns the TV on by setting a channel that isn't TVCHANNELTYPE_CHANNEL_NONE (which will turn it off)

## iChannel Values:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | 1 |
| 1 | 2 |
| 2 | Special |
| 3 | Script (Only For Use In Lester1. If You Don'T Know Why You Want To Use This Channel, You Don'T Want To Use This Channel.) |
| 4 | 3 (Requested For Use In Arcades In Mpheist3) |

