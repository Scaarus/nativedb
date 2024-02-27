---
ns: GRAPHICS
aliases: ["0xa328a24aaa6b7fdc"]
---
## TRIGGER_SCREENBLUR_FADE_IN

```c
// 0xA328A24AAA6B7FDC
bool TRIGGER_SCREENBLUR_FADE_IN(float Duration);
```

Gradually blurs the screen along Duration (in milliseconds) Once the fade in finishes, the screen will stay blurred until [`TRIGGER_SCREENBLUR_FADE_OUT`](#_0xEFACC8AEF94430D5) or [`DISABLE_SCREENBLUR_FADE`](#_0xDE81239437E8C5A8) is called

