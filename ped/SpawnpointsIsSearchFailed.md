---
ns: PED
aliases: ["0xf445de8da80a1792"]
---
## SPAWNPOINTS_IS_SEARCH_FAILED

```c
// 0xF445DE8DA80A1792
bool SPAWNPOINTS_IS_SEARCH_FAILED();
```

Returns TRUE if a search is in the failed state. Will assert if no search is active A search may enter the failed state if its duration exceeds the option iMaxSearchDuration specified when the search begins.

