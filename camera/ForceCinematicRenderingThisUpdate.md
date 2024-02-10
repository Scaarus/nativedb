---
ns: CAMERA
aliases: ["0xa41bcd7213805aac"]
---
## FORCE_CINEMATIC_RENDERING_THIS_UPDATE

```c
// 0xA41BCD7213805AAC
void FORCE_CINEMATIC_RENDERING_THIS_UPDATE(bool ActiveThisFrame);
```

Forces the cinematic mode to render this frame only. Will only render if there is a valid cinematic context.

If there is a cinematic camera rendering this cannot be overridden by the player.

