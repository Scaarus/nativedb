---
ns: PLAYER
aliases: ["0xbc8983f38f78ed51"]
---
## FORCE_CLEANUP

```c
// 0xBC8983F38F78ED51
void FORCE_CLEANUP(int ForceCleanupBitField);
```

This command will cause all scripts that are listening for the given force cleanup event to jump back to the [`HAS_FORCE_CLEANUP_OCCURRED`](#_0xC968670BFACE42D9) line and continue processing from there.


## Parameters
* **ForceCleanupBitField**: the type of force cleanup "event" to send out to all active scripts (Default value: `Force_Cleanup_Flag_Player_Killed_Or_Arrested`)
