---
ns: GRAPHICS
aliases: ["0xd8b9a8ac5608ff94"]
---
## DRAW_DEBUG_LINE_WITH_TWO_COLOURS

```c
// 0xD8B9A8AC5608FF94
void DRAW_DEBUG_LINE_WITH_TWO_COLOURS(Vector3 PositionFirst, Vector3 PositionSecond, int StartRed, int StartGreen, int StartBlue, int StartAlpha, int EndRed, int EndAlpha);
```

Draws a debug line startin in one clour and blending to another.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.

