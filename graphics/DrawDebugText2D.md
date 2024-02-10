---
ns: GRAPHICS
aliases: ["0xa3bb2e9555c05a8f"]
---
## DRAW_DEBUG_TEXT_2D

```c
// 0xA3BB2E9555C05A8F
void DRAW_DEBUG_TEXT_2D(string text, Vector3 Position, int Red, int Green, int Blue, int alpha_param);
```

Draws text to the screen. Vector x,y values should be in the range 0,0 -> 1,1.

RGB = integers between 0 and 255. Defaulted to blue.

This command draws to the screen game screen. The top left of the screen is 0,0 and the bottom right is 1,1. so all values should be bewteen these values.

