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
| 5 | Before Hud Standard |
| 6 | Before Hud Priority High |
| 7 | After Hud Priority Low |
| 8 | After Hud Standard |
| 9 | After Hud Priority High |
| 10 | After Fade Priority Low |
| 11 | After Fade Standard |
| 12 | After Fade Priority High |

