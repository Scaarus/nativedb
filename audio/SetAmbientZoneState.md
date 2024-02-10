---
ns: AUDIO
aliases: ["0xbda07e5950085e46"]
---
## SET_AMBIENT_ZONE_STATE

```c
// 0xBDA07E5950085E46
void SET_AMBIENT_ZONE_STATE(string zoneName, bool enabled, bool forceUpdate);
```

Enables/disables an ambient zone for the duration of this script

Use the 'forceUpdate' flag to force a zone to become disabled even if its currently active. The default disabling behaviour is that any state changes only get applied once the player leaves the zone.

