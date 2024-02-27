---
ns: GRAPHICS
aliases: ["0xf7b38b8305f1fe8b"]
---
## SET_TV_CHANNEL_PLAYLIST

```c
// 0xF7B38B8305F1FE8B
void SET_TV_CHANNEL_PLAYLIST(int iChannel, string playlistName, bool startFromNow);
```

Sets the passed channel to the passed playlist

## iChannel Values:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | 1 |
| 1 | 2 |
| 2 | Special |
| 3 | Script (Only For Use In Lester1. If You Don'T Know Why You Want To Use This Channel, You Don'T Want To Use This Channel.) |
| 4 | 3 (Requested For Use In Arcades In Mpheist3) |


## Parameters
* **iChannel**: 
* **playlistName**: 
* **startFromNow**: (Default value: `False`)
