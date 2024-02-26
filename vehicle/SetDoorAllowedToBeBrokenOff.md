---
ns: VEHICLE
aliases: ["0x2fa133a4a9d37ed8"]
---
## SET_DOOR_ALLOWED_TO_BE_BROKEN_OFF

```c
// 0x2FA133A4A9D37ED8
void SET_DOOR_ALLOWED_TO_BE_BROKEN_OFF(Vehicle vehicle, int DoorNumber, bool DoorBreakageAllowed);
```

Prevent a door from being broken off.

## DoorNumber Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 1 | Front Right |
| 2 | Rear Left |
| 3 | Rear Right |
| 4 | Bonnet |
| 5 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

