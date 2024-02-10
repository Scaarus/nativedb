---
ns: OBJECT
aliases: ["0x160aa1b32f6139b8"]
---
## DOOR_SYSTEM_GET_DOOR_STATE

```c
// 0x160AA1B32F6139B8
door_state_enum DOOR_SYSTEM_GET_DOOR_STATE(int doorEnumHash);
```

Get the state of a door managed by the door system

## Return Type Values:
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

