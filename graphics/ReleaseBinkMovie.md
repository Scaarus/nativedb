---
ns: GRAPHICS
aliases: ["0x04d950eefa4eed8c"]
---
## RELEASE_BINK_MOVIE

```c
// 0x04D950EEFA4EED8C
void RELEASE_BINK_MOVIE(int MovieId);
```

Frees the memory allocated to the movie.

This command should be called when you are finished with a movie. It frees up the memory allocated by [SET_BINK_MOVIE](#_0x338D9F609FD632DB).

