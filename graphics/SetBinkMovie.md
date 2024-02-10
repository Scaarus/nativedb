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

To display the movie, call PLAY_BINK_MOVIE every frame. Once you've finished with the movie, call RELEASE_BINK_MOVIE to free the memory.

