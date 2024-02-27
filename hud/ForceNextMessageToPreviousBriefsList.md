---
ns: HUD
aliases: ["0x57d760d55f54e071"]
---
## FORCE_NEXT_MESSAGE_TO_PREVIOUS_BRIEFS_LIST

```c
// 0x57D760D55F54E071
void FORCE_NEXT_MESSAGE_TO_PREVIOUS_BRIEFS_LIST(int PreviousBriefsOverride);
```

Determines which of the two previous briefs screens (dialogue or god text) the next line of text will appear in If the line of text wouldn't ordinarily have been added to either screen then it still won't appear in the previous briefs

## Values for `PreviousBriefsOverride`:
| Value | Name |
| --- | --- |
| 0 | No Override |
| 1 | Force Dialogue |
| 2 | Force God Text |

