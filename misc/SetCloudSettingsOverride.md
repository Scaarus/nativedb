---
ns: MISC
aliases: ["0x02deaac8f8ea7fe7"]
---
## SET_CLOUD_SETTINGS_OVERRIDE

```c
// 0x02DEAAC8F8EA7FE7
void SET_CLOUD_SETTINGS_OVERRIDE(string OverrideSettingsName);
```

overrides the clouds settings (which are normally controlled by the weather) with the named version


## Parameters
* **OverrideSettingsName**: the name of the settings to use, "NONE" or NULL to return to normal behavior
