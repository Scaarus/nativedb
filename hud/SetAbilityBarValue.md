---
ns: HUD
aliases: ["0x9969599ccff5d85e"]
---
## SET_ABILITY_BAR_VALUE

```c
// 0x9969599CCFF5D85E
void SET_ABILITY_BAR_VALUE(float fPercentage, float fMaxPercentage);
```

```
Sets the ability bar's values manually NOTE: this applies an override indefinitely, so turn it off with an fPercentage of -1 (any negative value)
```

## Parameters
* **fPercentage**: [0-100] value of bar being used, or -1 to turn it back to automatic. 0 hides it from display
* **fMaxPercentage**: [0-100] how much of the bar is considered the full extent
