---
ns: MISC
aliases: ["0x1e0b4dc0d990a4e7"]
---
## SET_FADE_OUT_AFTER_ARREST

```c
// 0x1E0B4DC0D990A4E7
void SET_FADE_OUT_AFTER_ARREST(bool DoFade);
```

```
Sets whether the screen fades out after an arrest has been intiated.

After each suppressed fade the variable is set back to false Note: The mission cleanup doesn't reset the variable so it's up to the script to call SET_FADE_OUT_AFTER_ARREST (true) when done with the particular mission.
```
