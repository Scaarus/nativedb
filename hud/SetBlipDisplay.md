---
ns: HUD
aliases: ["0x9029b2f3da924928"]
---
## SET_BLIP_DISPLAY

```c
// 0x9029B2F3DA924928
void SET_BLIP_DISPLAY(Blip blip, int display);
```

Change display mode for Radar blip

## Values for `display`:
| Value | Name |
| --- | --- |
| 0 | Nothing |
| 1 | Marker |
| 2 | Blip |
| 3 | Map (Used To Only Display This Blip On The Frontend Map (It Wont Display On The Radar Or Have A Marker)) |
| 4 | Both |
| 5 | Radar Only (Only Display Blip On The Radar (Opposite Of Display Map) - Note: No Markers Will Get Rendered) |
| 6 | Map Zoomed (Display This Blip On Radar And Only On Map When Map Is Zoomed Fully In) |
| 7 | Bigmap Full Only (Display On Zoomed Out Version Of The Bigmap Only) |
| 8 | Minimap Or Bigmap (Display On Normal Minimap Or Bigmap (But Not On The Full Zoomed Map)) |

