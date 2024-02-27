---
ns: HUD
aliases: ["0x632b2940c67f4ea9"]
---
## GET_MOUSE_EVENT

```c
// 0x632B2940C67F4EA9
bool GET_MOUSE_EVENT(Scaleform scaleform, int evtType, int iUID, int iContext);
```

Returns whether the mouse pointer is currently rolled over the instructional buttons.

## Values for `evtType`:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | Drag Out |
| 1 | Drag Over |
| 2 | Down |
| 3 | Move |
| 4 | Up |
| 5 | Press |
| 6 | Release |
| 7 | Release Outside |
| 8 | Roll Out |
| 9 | Roll Over |


iScaleformMovieId -- The scaleform movie id to check for mouse events evtType -- Type of mouse event that occurs (This will be written to if TRUE is returned) iUID -- Unique ID for the item that triggered the mouse event (This will be written to if TRUE is returned) iContext -- The context that this item occured. This can be a column index, submenu, etc. (This will be written to if TRUE is returned)

