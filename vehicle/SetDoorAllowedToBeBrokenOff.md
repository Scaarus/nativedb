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
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

