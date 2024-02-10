---
ns: GRAPHICS
aliases: ["0x108be26959a9d9bb"]
---
## UI3DSCENE_MAKE_PUSHED_PRESET_PERSISTENT

```c
// 0x108BE26959A9D9BB
void UI3DSCENE_MAKE_PUSHED_PRESET_PERSISTENT(bool Enabled);
```

This can be called *after* having pushed and patched a preset to automatically keep it rendering every frame until the persistent flag is disabled. This should only be used in cases where script is unable to push a preset every frame to keep it rendering (e.g.: script is paused). No other user can push new presets while UI3DSCENE_MAKE_PUSHED_PRESET_PERSISTENT is enabled.

