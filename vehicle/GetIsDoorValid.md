---
ns: VEHICLE
aliases: ["0x645f4b6e8499f632"]
---
## GET_IS_DOOR_VALID

```c
// 0x645F4B6E8499F632
bool GET_IS_DOOR_VALID(int DoorNumber);
```

```
returns true if the door is valid

Possible values for DoorNumber:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |
```
