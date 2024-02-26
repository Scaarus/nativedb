---
ns: MISC
aliases: ["0x0cf2b696bbf945ae"]
---
## UPDATE_ONSCREEN_KEYBOARD

```c
// 0x0CF2B696BBF945AE
int UPDATE_ONSCREEN_KEYBOARD();
```

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Pending |
| 1 | Success |
| 2 | Cancelled |
| 3 | Failed |

Updates the system keyboard, and returns its status. This should be called periodically until a non-PENDING status is returned.

