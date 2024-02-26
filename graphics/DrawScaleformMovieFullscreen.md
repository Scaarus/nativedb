---
ns: GRAPHICS
aliases: ["0x0df606929c105be1"]
---
## DRAW_SCALEFORM_MOVIE_FULLSCREEN

```c
// 0x0DF606929C105BE1
void DRAW_SCALEFORM_MOVIE_FULLSCREEN(Scaleform scaleform, int R, int G, int B, int A, int StereoFlag);
```

Renders a scaleform movie to the screen always at full screen

movie id (retrieved from [REQUEST_SCALEFORM_MOVIE](#_0x11FE353CF9733E6F)). The size is always

movies are drawn in order, with the latest drawn on top.

