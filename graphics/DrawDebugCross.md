---
ns: GRAPHICS
aliases: ["0x73b1189623049839"]
---
## DRAW_DEBUG_CROSS

```c
// 0x73B1189623049839
void DRAW_DEBUG_CROSS(Vector3 PositionMin, float Size, int Red, int Green, int Blue, int alpha_param);
```

Draws a cross at the given vector.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.


## Parameters
* **PositionMin**: 
* **Size**: 
* **Red**: (Default value: `0`)
* **Green**: (Default value: `0`)
* **Blue**: (Default value: `255`)
* **alpha_param**: (Default value: `255`)
