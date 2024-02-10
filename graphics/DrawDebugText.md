---
ns: GRAPHICS
aliases: ["0x3903e216620488e8"]
---
## DRAW_DEBUG_TEXT

```c
// 0x3903E216620488E8
void DRAW_DEBUG_TEXT(string text, Vector3 Position, int Red, int Green, int Blue, int alpha_param);
```

Draws text at a world coord.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.

