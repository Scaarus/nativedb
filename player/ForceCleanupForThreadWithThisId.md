---
ns: PLAYER
aliases: ["0xf745b37630df176b"]
---
## FORCE_CLEANUP_FOR_THREAD_WITH_THIS_ID

```c
// 0xF745B37630DF176B
void FORCE_CLEANUP_FOR_THREAD_WITH_THIS_ID(int Thread_Id, int ForceCleanupBitField);
```

This command works in the same way as [`FORCE_CLEANUP`](#_0xBC8983F38F78ED51) but only affects the script thread with the given thread ID


## Parameters
* **Thread_Id**: 
* **ForceCleanupBitField**: (Default value: `Force_Cleanup_Flag_Player_Killed_Or_Arrested`)
