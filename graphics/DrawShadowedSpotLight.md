---
ns: GRAPHICS
aliases: ["0x5bca583a583194db"]
---
## DRAW_SHADOWED_SPOT_LIGHT

```c
// 0x5BCA583A583194DB
void DRAW_SHADOWED_SPOT_LIGHT(Vector3 Position, Vector3 Direction, int R, int G, int B, float Falloff, float Intensity, float InnerAngle, float OuterAngle, float Exp, int lightNum);
```

Adds a shadowed spot light with the a scene. Each one needs its own lightNum (just start at 0 and increment) for each new shadowed light added in the script.

RGB = integers between 0 and 255

