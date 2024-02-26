---
ns: GRAPHICS
aliases: ["0x338d9f609fd632db"]
---
## SET_BINK_MOVIE

```c
// 0x338D9F609FD632DB
int SET_BINK_MOVIE(string MovieName);
```

Allocates memory and loads the specified movie file.

To display the movie, call [PLAY_BINK_MOVIE](#_0x70D2CC8A542A973C) every frame. Once you've finished with the movie, call [RELEASE_BINK_MOVIE](#_0x04D950EEFA4EED8C) to free the memory.

