---
ns: CUTSCENE
aliases: ["0x71b74d2ae19338d0"]
---
## IS_CUTSCENE_PLAYBACK_FLAG_SET

```c
// 0x71B74D2AE19338D0
bool IS_CUTSCENE_PLAYBACK_FLAG_SET(int flags);
```

Get the flags the cutscene was started with.

## flags Values:
| Value | Name |
| --- | --- |
| 1 | Requested From Widget |
| 2 | Requested Directly From Skip |
| 4 | Requested From Z Skip |
| 8 | Requested In Mission |
| 16 | Playback Force Load Audio Event |

