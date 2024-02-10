---
ns: GRAPHICS
aliases: ["0xf1cea8a4198d8e9a"]
---
## UI3DSCENE_PUSH_PRESET

```c
// 0xF1CEA8A4198D8E9A
bool UI3DSCENE_PUSH_PRESET(string presetName);
```

Sets the preset as the current one; this needs to be done before assigning peds to the preset slots It will return false if the preset doesn't exist or if the system is already in use.

