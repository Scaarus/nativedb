---
ns: MISC
aliases: ["0x4a18e01df2c87b86"]
---
## SET_FADE_OUT_AFTER_DEATH

```c
// 0x4A18E01DF2C87B86
void SET_FADE_OUT_AFTER_DEATH(bool DoFade);
```

Sets whether the screen fades out after death

After each suppressed fade the variable is set back to false Note: The mission cleanup doesn't reset the variable so it's up to the script to call [SET_FADE_OUT_AFTER_ARREST](#_0x1E0B4DC0D990A4E7) (true) when done with the particular mission.

