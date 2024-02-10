---
ns: STATS
aliases: ["0xe0e854f5280fb769"]
---
## STAT_GET_NUMBER_OF_DAYS

```c
// 0xE0E854F5280FB769
int STAT_GET_NUMBER_OF_DAYS(int Hash);
```

This command can be used on stats that store timer values in milliseconds (like TOTAL_PLAYING_TIME) but their types are are too big to be converted to hours in script.

