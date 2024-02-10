---
ns: GRAPHICS
aliases: ["0x7fdfade676aa3cb0"]
---
## DRAW_DEBUG_LINE

```c
// 0x7FDFADE676AA3CB0
void DRAW_DEBUG_LINE(Vector3 PositionFirst, Vector3 PositionSecond, int red, int green, int blue, int alpha_param);
```

Draws a debug line bewteen the 2 vectors.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.

