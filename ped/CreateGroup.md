---
ns: PED
aliases: ["0x90370ebe0fee1a3d"]
---
## CREATE_GROUP

```c
// 0x90370EBE0FEE1A3D
Group CREATE_GROUP(int DefaultTaskType);
```

Creates a group.

## Values for `DefaultTaskType`:
| Value | Name |
| --- | --- |
| 0 | Follow Any Means |
| 1 | Follow Limited |
| 2 | Stand Still |
| 3 | Chat |
| 4 | Sit In Leader Car |
| 5 | Random |


Every frame, the code automatically removes any group which doesn't have any leader/members. This means that you have to set a group leader in the same frame as the group is created, as otherwise you'll get an assert about the group ID being out of range (i.e. the group doesn't exist) The Player already has a group so a group doens't need to be created for them.

