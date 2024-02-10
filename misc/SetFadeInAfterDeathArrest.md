---
ns: MISC
aliases: ["0xda66d2796ba33f12"]
---
## SET_FADE_IN_AFTER_DEATH_ARREST

```c
// 0xDA66D2796BA33F12
void SET_FADE_IN_AFTER_DEATH_ARREST(bool DoFade);
```

Sets whether the screen fades back in after a death arrest has been intiated.

After each suppressed fade the variable is set back to false Note: The mission cleanup doesn't reset the variable so it's up to the script to leave call SET_FADE_IN_AFTER_DEATH_ARREST (true) when done with the particular mission.

