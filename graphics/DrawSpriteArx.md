---
ns: GRAPHICS
aliases: ["0x2d3b147afad49de0"]
---
## DRAW_SPRITE_ARX

```c
// 0x2D3B147AFAD49DE0
void DRAW_SPRITE_ARX(string pTextureDictionaryName, string pTextureName, float CentreX, float CentreY, float Width, float Height, float Rotation, int R, int G, int B, int A, bool DoStereorize, bool UseNearest);
```

same as DRAW_SPRITE(), but correctly rotates sprites with inverted screen Aspect Ratio applied to all X coords:

