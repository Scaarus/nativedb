---
ns: HUD
aliases: ["0xd2049635deb9c375"]
---
## UPDATE_RADAR_ZOOM_TO_BLIP

```c
// 0xD2049635DEB9C375
void UPDATE_RADAR_ZOOM_TO_BLIP();
```

```
zooms in/out enough so that the passed blip is on the edge of the minimap

Must be called sparingly as it re-inits the range check for a blip. Call this if you are zoomed to a blip and the blip has moved and you want the minimap to re-zoom to it
```
