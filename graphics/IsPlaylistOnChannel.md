---
ns: GRAPHICS
aliases: ["0x1f710bff7dae6261"]
---
## IS_PLAYLIST_ON_CHANNEL

```c
// 0x1F710BFF7DAE6261
bool IS_PLAYLIST_ON_CHANNEL(int iChannel, int nameHash);
```

Returns if a specific playlist is set on the specified channel

## Values for `iChannel`:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | 1 |
| 1 | 2 |
| 2 | Special |
| 3 | Script (Only For Use In Lester1. If You Don'T Know Why You Want To Use This Channel, You Don'T Want To Use This Channel.) |
| 4 | 3 (Requested For Use In Arcades In Mpheist3) |

