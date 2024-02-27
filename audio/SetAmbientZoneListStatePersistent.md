---
ns: AUDIO
aliases: ["0xf3638dae8c4045e1"]
---
## SET_AMBIENT_ZONE_LIST_STATE_PERSISTENT

```c
// 0xF3638DAE8C4045E1
void SET_AMBIENT_ZONE_LIST_STATE_PERSISTENT(string zoneListName, bool enabled, bool forceUpdate);
```

Enables/disables a list of ambient zones persistently. This change will be saved to the user's savegame

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.


## Parameters
* **zoneListName**: 
* **enabled**: 
* **forceUpdate**: (Default value: `False`)
