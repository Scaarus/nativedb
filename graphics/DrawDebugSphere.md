---
ns: GRAPHICS
aliases: ["0xaad68e1ab39da632"]
---
## DRAW_DEBUG_SPHERE

```c
// 0xAAD68E1AB39DA632
void DRAW_DEBUG_SPHERE(Vector3 Position, float Range, int Red, int Green, int Blue, int alpha_param);
```

Draws a debug sphere.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.

