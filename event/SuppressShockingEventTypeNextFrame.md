---
ns: EVENT
aliases: ["0x3fd2ec8bf1f1cf30"]
---
## SUPPRESS_SHOCKING_EVENT_TYPE_NEXT_FRAME

```c
// 0x3FD2EC8BF1F1CF30
void SUPPRESS_SHOCKING_EVENT_TYPE_NEXT_FRAME(int eventShockingLevel);
```

Prevents shocking events of a certain type from being added to the world next frame.

## eventShockingLevel Values:
| Value | Name |
| --- | --- |
| 253 | Interesting |
| 254 | Affects Others |
| 255 | Potentially Dangerous |
| 256 | Dangerous |
| 257 | Serious Danger |
