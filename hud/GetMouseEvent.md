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

## evtType Values:
| Value | Name |
| --- | --- |
| -1 | None |
| 0 | Drag Out |
| 873 | Drag Over |
| 874 | Down |
| 875 | Move |
| 876 | Up |
| 877 | Press |
| 878 | Release |
| 879 | Release Outside |
| 880 | Roll Out |
| 881 | Roll Over |
| 882 | Max |


iScaleformMovieId -- The scaleform movie id to check for mouse events evtType -- Type of mouse event that occurs (This will be written to if TRUE is returned) iUID -- Unique ID for the item that triggered the mouse event (This will be written to if TRUE is returned) iContext -- The context that this item occured. This can be a column index, submenu, etc. (This will be written to if TRUE is returned)

