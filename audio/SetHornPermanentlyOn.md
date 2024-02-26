---
ns: AUDIO
aliases: ["0x9c11908013ea4715"]
---
## SET_HORN_PERMANENTLY_ON

```c
// 0x9C11908013EA4715
void SET_HORN_PERMANENTLY_ON(Vehicle vehicle);
```

Turns the horn on - on every frame, not choosing a pattern of it's own. Needs called every frame. Will time-out after [SET_HORN_PERMANENTLY_ON_TIME](#_0x9D3AF56E94C9AE98)(VEHICLE_INDEX VehicleIndex, FLOAT HornTime)

