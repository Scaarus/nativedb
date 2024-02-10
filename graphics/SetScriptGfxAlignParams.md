---
ns: GRAPHICS
aliases: ["0xf5a2c681787e579d"]
---
## SET_SCRIPT_GFX_ALIGN_PARAMS

```c
// 0xF5A2C681787E579D
void SET_SCRIPT_GFX_ALIGN_PARAMS(float offsetX, float offsetY, float sizeX, float sizeY);
```

```
Sets the additional alignment parameters offsetX, offsetY : Value to offset all x,y coords passed to 2d renderer. sizeX : If you are aligned to the right of the screen it assumes the x size of everything is this. This makes the calculations for positioning multiple UI elements of different sizes easier. Set this to the size of the largest element sizeY : If you are aligned to the bottom of the screen it assumes the y size of everything is this. As above set this to the size of largest element
```
