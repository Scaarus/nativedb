---
ns: VEHICLE
aliases: ["0x407dc5e97db1a4d3"]
---
## SET_VEHICLE_HOMING_LOCKEDONTO_STATE

```c
// 0x407DC5E97DB1A4D3
void SET_VEHICLE_HOMING_LOCKEDONTO_STATE(Vehicle vehicle, int LockOnState);
```

```
Sets the vehicle locked-onto state for a target vehicle (for when we need to emulate the homing code)

Possible values for LockOnState:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Acquiring |
| 2 | Acquired |
```
