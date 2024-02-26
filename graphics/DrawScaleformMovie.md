---
ns: GRAPHICS
aliases: ["0x54972adaf0294a93"]
---
## DRAW_SCALEFORM_MOVIE

```c
// 0x54972ADAF0294A93
void DRAW_SCALEFORM_MOVIE(Scaleform scaleform, float CentreX, float CentreY, float Width, float Height, int R, int G, int B, int A, int StereoFlag);
```

Renders a scaleform movie to the screen.

movie id (retrieved from [REQUEST_SCALEFORM_MOVIE](#_0x11FE353CF9733E6F)), position & size, StereoFlag(0 = no stereo, 1 = reticule stereo, 2 = normal stereo)

movies are drawn in order, with the latest drawn on top.

