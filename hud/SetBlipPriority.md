---
ns: HUD
aliases: ["0xae9fc9ef6a9fac79"]
---
## SET_BLIP_PRIORITY

```c
// 0xAE9FC9EF6A9FAC79
void SET_BLIP_PRIORITY(Blip blip, int priority);
```

Change priority for Radar blip

## priority Values:
| Value | Name |
| --- | --- |
| 0 | BLIPPRIORITY_LOW_LOWEST |
| 1 | BLIPPRIORITY_LOWEST |
| 2 | BLIPPRIORITY_LOW |
| 3 | BLIPPRIORITY_LOW_MED |
| 4 | BLIPPRIORITY_MED |
| 5 | BLIPPRIORITY_MED_HIGH |
| 6 | BLIPPRIORITY_HIGH |
| 7 | BLIPPRIORITY_HIGH_HIGHEST |
| 8 | BLIPPRIORITY_HIGHEST |
| 9 | BLIP_PRIORITY_HIGHEST_SPECIAL_LOW (need additional added in for 1730606) |
| 10 | BLIP_PRIORITY_HIGHES_SPECIAL_MED (need additional priority added in for 1730606) |
| 11 | BLIP_PRIORITY_HIGHEST_SPECIAL_HIGH (need additional priority added in for 1730606) |
| 12 | BLIPPRIORITY_OVER_CENTRE_BLIP |

