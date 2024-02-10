---
ns: GRAPHICS
aliases: ["0x2201c576facaebe8"]
---
## SET_TV_CHANNEL_PLAYLIST_AT_HOUR

```c
// 0x2201C576FACAEBE8
void SET_TV_CHANNEL_PLAYLIST_AT_HOUR(int iChannel, string playlistName, int iHour);
```

Sets the passed channel to the passed playlist, and start time of that playlist in hours (0-23)

## iChannel Values:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | 1 |
| 13 | 2 |
| 14 | Special |
| 15 | Script Only For Use In Lester1. If You Don'T Know Why You Want To Use This Channel, You Don'T Want To Use This Channel. |
| 16 | 3 Requested For Use In Arcades In Mpheist3 |

