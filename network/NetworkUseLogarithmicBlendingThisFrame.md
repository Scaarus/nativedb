---
ns: NETWORK
aliases: ["0xcd71a4ecab22709e"]
---
## NETWORK_USE_LOGARITHMIC_BLENDING_THIS_FRAME

```c
// 0xCD71A4ECAB22709E
void NETWORK_USE_LOGARITHMIC_BLENDING_THIS_FRAME(Entity entity);
```

Flags the specified network entity to use logarithmic network blending for this frame only, this blending mode prevents overshooting the target and can make things look smoother if the target object is not behaving physically (i.e. being positioned by script each frame) at the expense of lagging behind. *IMPORTANT* - This needs to be called every frame this behaviour is desired

