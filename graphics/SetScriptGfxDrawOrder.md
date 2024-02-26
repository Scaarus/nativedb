---
ns: GRAPHICS
aliases: ["0x61bb1d9b3a95d802"]
---
## SET_SCRIPT_GFX_DRAW_ORDER

```c
// 0x61BB1D9B3A95D802
void SET_SCRIPT_GFX_DRAW_ORDER(int iDrawOrder);
```

Sets scripted gfx draw order. The default setting is GFX_ORDER_AFTER_HUD

## iDrawOrder Values:
| Value | Name |
| --- | --- |
| 0 | Before Hud Priority Low |
| 1 | Before Hud (Standard) |
| 2 | Before Hud Priority High |
| 3 | After Hud Priority Low |
| 4 | After Hud (Standard) |
| 5 | After Hud Priority High |
| 6 | After Fade Priority Low |
| 7 | After Fade (Standard) |
| 8 | After Fade Priority High |

