---
ns: STATS
aliases: ["0x11ff1c80276097ed"]
---
## PRESENCE_EVENT_UPDATESTAT_INT

```c
// 0x11FF1C80276097ED
void PRESENCE_EVENT_UPDATESTAT_INT(int Hash, int value, int value2);
```

Send a presence event regarding a significant update of a stat. Will result in a EVENT_NETWORK_PRESENCE_STAT_UPDATE being received by all your friends

