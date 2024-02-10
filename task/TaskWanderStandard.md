---
ns: TASK
aliases: ["0xbb9ce077274f6a1b"]
---
## TASK_WANDER_STANDARD

```c
// 0xBB9CE077274F6A1B
void TASK_WANDER_STANDARD(Ped ped, float Heading, int WanderFlags);
```

Tells a ped to wander. If you dont pass in a heading it will be randomized when tasks starts

## WanderFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Keep Moving Whilst Waiting For First Path |

