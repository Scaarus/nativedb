---
ns: STATS
aliases: ["0x6d3a430d1a809179"]
---
## SET_PACKED_STAT_INT_CODE

```c
// 0x6D3A430D1A809179
void SET_PACKED_STAT_INT_CODE(int stat, int value, int overrideCharSlot);
```

NEW NATIVE HELPER FUNCTIONS TO MANIPULATE PACKED STATS. Only use 'overrideCharSlot' if you want to override using the current selected character. Make sure its a correct character index. 0 to 2 on SP and 0 to 1 on MP.

