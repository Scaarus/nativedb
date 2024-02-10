---
ns: PED
aliases: ["0xf9d9f7f2db8e2fa0"]
---
## GET_PED_COMBAT_RANGE

```c
// 0xF9D9F7F2DB8E2FA0
combat_range GET_PED_COMBAT_RANGE(Ped ped);
```

Gets the current range that the ped will engage the targets during combat.

## Return Type Values:
| Value | Name |
| --- | --- |
| 200 | Near Keeps Within 5-15M |
| 201 | Medium Keeps Within 7-30M |
| 202 | Far Keeps Within 15-40M |
| 203 | Very Far Keeps Within 22-45M |

