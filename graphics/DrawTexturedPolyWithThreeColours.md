---
ns: GRAPHICS
aliases: ["0x736d7aa1b750856b"]
---
## DRAW_TEXTURED_POLY_WITH_THREE_COLOURS

```c
// 0x736D7AA1B750856B
void DRAW_TEXTURED_POLY_WITH_THREE_COLOURS(Vector3 PositionFirst, Vector3 PositionSecond, Vector3 PositionThird, Vector3 RGB1, int A1, Vector3 RGB2, int A2, Vector3 RGB3, int A3, string TextureDictionaryName, string TextureName, Vector3 UV1, Vector3 UV2, Vector3 UV3);
```

Draws textured poly between the 3 vectors with 3 Colours

Colours and alpha range are 0-255. RGB componenets are passed as floats (0.0-255.0) in XYZ of the vector. UVs are passed in XY components of the vector (Z is ignored).

Call this command every frame.

