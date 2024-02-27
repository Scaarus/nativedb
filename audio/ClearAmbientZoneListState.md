---
ns: AUDIO
aliases: ["0x120c48c614909fa4"]
---
## CLEAR_AMBIENT_ZONE_LIST_STATE

```c
// 0x120C48C614909FA4
void CLEAR_AMBIENT_ZONE_LIST_STATE(string zoneListName, bool forceUpdate);
```

Resets the list of ambient zones' enabled/disabled status back to their values before they were modified by this script

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.


## Parameters
* **zoneListName**: 
* **forceUpdate**: (Default value: `False`)
