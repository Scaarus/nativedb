---
ns: HUD
aliases: ["0xf98e4b3e56afc7b1"]
---
## SET_RADAR_ZOOM_TO_BLIP

```c
// 0xF98E4B3E56AFC7B1
void SET_RADAR_ZOOM_TO_BLIP(Blip blip, float fOffset);
```

zooms in/out enough so that the passed blip is on the edge of the minimap

Must be called every frame - keeps it locked to a blip


## Parameters
* **blip**: 
* **fOffset**: (Default value: `0`)
