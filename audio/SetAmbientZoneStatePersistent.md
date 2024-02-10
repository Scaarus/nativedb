---
ns: AUDIO
aliases: ["0x1d6650420cec9d3b"]
---
## SET_AMBIENT_ZONE_STATE_PERSISTENT

```c
// 0x1D6650420CEC9D3B
void SET_AMBIENT_ZONE_STATE_PERSISTENT(string zoneName, bool enabled, bool forceUpdate);
```

Enables/disables an ambient zones persistently. This change will be saved to the user's savegame

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.

