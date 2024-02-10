---
ns: VEHICLE
aliases: ["0x0581730ab9380412"]
---
## SET_VEHICLE_TURRET_TARGET

```c
// 0x0581730AB9380412
void SET_VEHICLE_TURRET_TARGET(Vehicle vehicle, int TurretIndex, Vector3 TargetPosition, bool SnapToPosition);
```

If TurretIndex is -1 all turrets will point at the target.

Sets the target position for a turret to point at

