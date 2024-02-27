---
ns: PLAYER
aliases: ["0x4c68ddddf0097317"]
---
## FORCE_CLEANUP_FOR_ALL_THREADS_WITH_THIS_NAME

```c
// 0x4C68DDDDF0097317
void FORCE_CLEANUP_FOR_ALL_THREADS_WITH_THIS_NAME(string pName, int ForceCleanupBitField);
```

This command works in the same way as [`FORCE_CLEANUP`](#_0xBC8983F38F78ED51) but only affects script threads with the given name


## Parameters
* **pName**: 
* **ForceCleanupBitField**: (Default value: `Force_Cleanup_Flag_Player_Killed_Or_Arrested`)
