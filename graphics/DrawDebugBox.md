---
ns: GRAPHICS
aliases: ["0x083a2ca4f2e573bd"]
---
## DRAW_DEBUG_BOX

```c
// 0x083A2CA4F2E573BD
void DRAW_DEBUG_BOX(Vector3 PositionMin, Vector3 PositionMax, int Red, int Green, int Blue, int alpha_param);
```

Draws a debug axis aligned box.

Defaulted to blue. Colours and alpha range are

Call this command every frame. Only runs in dev and bank release. Requires script -> Draw Debug Lines And Spheres widget to be active.


## Parameters
* **PositionMin**: 
* **PositionMax**: 
* **Red**: (Default value: `0`)
* **Green**: (Default value: `0`)
* **Blue**: (Default value: `255`)
* **alpha_param**: (Default value: `255`)
