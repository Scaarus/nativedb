---
ns: AUDIO
aliases: ["0x218dd44aaac964ff"]
---
## CLEAR_AMBIENT_ZONE_STATE

```c
// 0x218DD44AAAC964FF
void CLEAR_AMBIENT_ZONE_STATE(string zoneName, bool forceUpdate);
```

Resets the ambient zone enabled/disabled status to its value before it was modified by this script

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.


## Parameters
* **zoneName**: 
* **forceUpdate**: (Default value: `False`)
