---
ns: STATS
aliases: ["0xe07bca305b82d2fd"]
---
## STAT_SAVE

```c
// 0xE07BCA305B82D2FD
bool STAT_SAVE(int slot, bool doAssert, int saveType, int saveReason);
```

Default behaviour is to save the defaul slot (0) and the current slot that the player is using, ie, the value set in stat MPPLY_LAST_MP_CHAR. If you want a diferent slot saved you can pass in a value - 1 to max number os player slots.

## saveType Values:
| Value | Name |
| --- | --- |
| 38 |  |
