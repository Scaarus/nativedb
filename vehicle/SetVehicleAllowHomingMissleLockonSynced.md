---
ns: VEHICLE
aliases: ["0x1dda078d12879eee"]
---
## SET_VEHICLE_ALLOW_HOMING_MISSLE_LOCKON_SYNCED

```c
// 0x1DDA078D12879EEE
void SET_VEHICLE_ALLOW_HOMING_MISSLE_LOCKON_SYNCED(Vehicle vehicle, bool AllowHomingMissileLockon, bool IgnoreMisisonVehCheck);
```

Allow a MISSION vehicle to disable homing missle targetting (synced over network). This is a different flag to "[SET_VEHICLE_ALLOW_HOMING_MISSLE_LOCKON](#_0x7D6F9A3EF26136A0)", please ensure it's setcleared accordingly!

