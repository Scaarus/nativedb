---
ns: AUDIO
aliases: ["0x9748fa4de50cce3e"]
---
## SET_AMBIENT_ZONE_LIST_STATE

```c
// 0x9748FA4DE50CCE3E
void SET_AMBIENT_ZONE_LIST_STATE(string zoneListName, bool enabled, bool forceUpdate);
```

```
Enables/disables a list of ambient zones for the duration of this script

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.
```
