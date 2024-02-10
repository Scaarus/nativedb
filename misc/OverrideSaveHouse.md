---
ns: MISC
aliases: ["0x1162ea8ae9d24eea"]
---
## OVERRIDE_SAVE_HOUSE

```c
// 0x1162EA8AE9D24EEA
bool OVERRIDE_SAVE_HOUSE(bool Override, Vector3 vecCoords, float fHeading, bool IsAnAutosave);
```

Call this with bOverride=TRUE to force the player to respawn at vecCoords with fHeading instead of at a savehouse after a load. These settings will be applied to all saves until you call the command again with bOverride=FALSE


## Parameters
* **Override**: 
* **vecCoords**: 
* **fHeading**: 
* **IsAnAutosave**: some savehouses are flagged by SET_SAVE_HOUSE as not being available for autosaves. Pass TRUE for this parameter to ignore those savehouses when finding the closest one.
