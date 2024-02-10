---
ns: STATS
aliases: ["0xda7ebfc49ae3f1b0"]
---
## GET_PACKED_STAT_BOOL_CODE

```c
// 0xDA7EBFC49AE3F1B0
bool GET_PACKED_STAT_BOOL_CODE(int stat, int overrideCharSlot);
```

NEW NATIVE HELPER FUNCTIONS TO MANIPULATE PACKED STATS. Only use 'overrideCharSlot' if you want to override using the current selected character. Make sure its a correct character index. 0 to 2 on SP and 0 to 1 on MP.

