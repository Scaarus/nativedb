---
ns: GRAPHICS
aliases: ["0xcf537fde4fbd4ce5"]
---
## DRAW_SCALEFORM_MOVIE_FULLSCREEN_MASKED

```c
// 0xCF537FDE4FBD4CE5
void DRAW_SCALEFORM_MOVIE_FULLSCREEN_MASKED(Scaleform scaleform, Scaleform scaleform, int R, int G, int B, int A);
```

Renders two movies with masking between.

movie id (retrieved from [REQUEST_SCALEFORM_MOVIE](#_0x11FE353CF9733E6F)). The size is always

movies are drawn in order, with the latest drawn on top.

