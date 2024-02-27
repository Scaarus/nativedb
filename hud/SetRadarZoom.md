---
ns: HUD
aliases: ["0x096ef57a0c999bba"]
---
## SET_RADAR_ZOOM

```c
// 0x096EF57A0C999BBA
void SET_RADAR_ZOOM(int ZoomValue);
```

modifys the zoom value of the radar between 0 (no zoom), and 1 (max zoom in) and 1100 (max zoom out).

DP: I want to phase this out, please use [`SET_RADAR_ZOOM_PRECISE`](#_0xBD12C5EEE184C337) instead on any future use!

