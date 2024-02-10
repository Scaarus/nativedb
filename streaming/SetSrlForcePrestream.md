---
ns: STREAMING
aliases: ["0xf8155a7f03ddfc8e"]
---
## SET_SRL_FORCE_PRESTREAM

```c
// 0xF8155A7F03DDFC8E
void SET_SRL_FORCE_PRESTREAM(int forcePrestream);
```

Enable or disable forced prestreaming for cutscenes. If enabled, the SRL will always preload map data for the first frame of a cutscene, even if it is far away. BE CAREFUL when using this function. Only use it when you are CERTAIN that the current camera position and the first frame of the cutscene can't get too far away, and when you're certain that the two scenes are not particularly rich in entities. Otherwise, you will crash with a pool overflow.

## forcePrestream Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 21 | Force On 1 |
| 22 | Force Off 2 |
| 23 | Force Completely Off 3 |

