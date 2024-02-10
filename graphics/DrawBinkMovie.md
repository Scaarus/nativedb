---
ns: GRAPHICS
aliases: ["0x7118e83eeb9f7238"]
---
## DRAW_BINK_MOVIE

```c
// 0x7118E83EEB9F7238
void DRAW_BINK_MOVIE(int MovieId, float CentreX, float CentreY, float Width, float Height, float Rotation, int R, int G, int B, int A);
```

Draws a movie to the screen.

CentreX and CentreY define the centre point of the movie. between 0 (top left) and 1 (bottom right) RGBA set between 0 and 255 Rotataion : Rotation is measured in degrees.

Before you can use this command you have to load the movie using SET_BINK_MOVIE.

