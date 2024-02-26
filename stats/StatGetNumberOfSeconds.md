---
ns: STATS
aliases: ["0x2ce056ff3723f00b"]
---
## STAT_GET_NUMBER_OF_SECONDS

```c
// 0x2CE056FF3723F00B
int STAT_GET_NUMBER_OF_SECONDS(int Hash);
```

This command can be used on stats that store timer values in milliseconds (like TOTAL_PLAYING_TIME) but their types are are too big to be converted to hours in script.

