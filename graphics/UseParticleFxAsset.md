---
ns: GRAPHICS
aliases: ["0x6c38af3693a69a91"]
---
## USE_PARTICLE_FX_ASSET

```c
// 0x6C38AF3693A69A91
void USE_PARTICLE_FX_ASSET(string ptFxAssetName);
```

Enables the script to use a particle effect from a named asset (as opposed to the particle asset assigned to the script)
This must be called directly before every START_PARTICLE_FX_ command that needs it

