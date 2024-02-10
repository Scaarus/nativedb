---
ns: HUD
aliases: ["0x2aee8f8390d2298c"]
---
## SET_BLIP_FADE

```c
// 0x2AEE8F8390D2298C
void SET_BLIP_FADE(Blip blip, int DestinationAlpha, int FadeDurationInMilliseconds);
```

Starts fading a blip from its current alpha value to the DestinationAlpha

DestinationAlpha has to be between 0 and 255 (inclusive)

