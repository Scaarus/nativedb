---
ns: SOCIALCLUB
aliases: ["0xfe4c1d0d3b9cc17e"]
---
## SC_TRANSITION_NEWS_SHOW_TIMED

```c
// 0xFE4C1D0D3B9CC17E
bool SC_TRANSITION_NEWS_SHOW_TIMED(Scaleform scaleform, int iStoryOnscreenDuration);
```

Start and show the transition news. If a news story hasn't been queued, it will queue one. moveID - to make requests for scaleform on iStoryOnscreenDuration - the amount of time (in ms) to display each story for. If this value == 0, then the news controller will only show one news item and never transition to another.

