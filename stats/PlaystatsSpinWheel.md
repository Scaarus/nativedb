---
ns: STATS
aliases: ["0x6731de84a38bfad0"]
---
## PLAYSTATS_SPIN_WHEEL

```c
// 0x6731DE84A38BFAD0
void PLAYSTATS_SPIN_WHEEL(int contentId, int spintType, int rewardType, int rewardItem);
```

```
Metric fires at the end of the wheel spin (when the player choses to play only - do not send a metric if the player never pushes x to stop the wheel after being knocked out)
```
