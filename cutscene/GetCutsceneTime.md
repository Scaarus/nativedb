---
ns: CUTSCENE
aliases: ["0xe625beabbaffdab9"]
---
## GET_CUTSCENE_TIME

```c
// 0xE625BEABBAFFDAB9
int GET_CUTSCENE_TIME();
```

Gets the current time in milliseconds on the whole concat scene time line.. Note: If you've specified a concat list to play, this value will not be continuous (it will jump when skipping over the concat sections you exclude). IF you need the actual time the scene has been playing for use GET_CUTSCENE_PLAY_TIME() below. || \ e.g. for a scene like this: | A (2secs) | B (3 secs) | C (2 secs) | D (3 secs) | if your concat list chooses to play A & C (omitting B and D) and the cutscene is half way through section C, this command will return 6 seconds (the current time on the whole concat timeline) even though the scene has only been playing for 3 seconds from the player's perspective.

