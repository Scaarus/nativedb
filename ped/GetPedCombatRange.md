---
ns: PED
aliases: ["0xf9d9f7f2db8e2fa0"]
---
## GET_PED_COMBAT_RANGE

```c
// 0xF9D9F7F2DB8E2FA0
int GET_PED_COMBAT_RANGE(Ped ped);
```

Gets the current range that the ped will engage the targets during combat. 

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Near (Keeps Within 5-15M) |
| 1 | Medium (Keeps Within 7-30M) |
| 2 | Far (Keeps Within 15-40M) |
| 3 | Very Far (Keeps Within 22-45M) |

