---
ns: OBJECT
aliases: ["0x6bab9442830c7f53"]
---
## DOOR_SYSTEM_SET_DOOR_STATE

```c
// 0x6BAB9442830C7F53
void DOOR_SYSTEM_SET_DOOR_STATE(int doorEnumHash, int state, bool network, bool flushState);
```

Set the state of a door managed by the door system

## state Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Unlocked |
| 1 | Locked |
| 2 | Force Locked Until Out Of Area |
| 3 | Force Unlocked This Frame |
| 4 | Force Locked This Frame |
| 5 | Force Open This Frame |
| 6 | Force Closed This Frame |

