---
ns: VEHICLE
aliases: ["0x3e933cff7b111c22"]
---
## IS_VEHICLE_DOOR_FULLY_OPEN

```c
// 0x3E933CFF7B111C22
bool IS_VEHICLE_DOOR_FULLY_OPEN(Vehicle vehicle, int DoorNumber);
```

```
Checks that a vehicle door is open

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
