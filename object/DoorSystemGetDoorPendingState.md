---
ns: OBJECT
aliases: ["0x4bc2854478f3a749"]
---
## DOOR_SYSTEM_GET_DOOR_PENDING_STATE

```c
// 0x4BC2854478F3A749
door_state_enum DOOR_SYSTEM_GET_DOOR_PENDING_STATE(int doorEnumHash);
```

```
Get the pending state of a door managed by the door system

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Unlocked |
| 1 | Locked |
| 2 | Force Locked Until Out Of Area |
| 3 | Force Unlocked This Frame |
| 4 | Force Locked This Frame |
| 5 | Force Open This Frame |
| 6 | Force Closed This Frame |
```
