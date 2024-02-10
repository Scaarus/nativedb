---
ns: PATH
aliases: ["0x125bf4abfc536b09"]
---
## IS_POINT_ON_ROAD

```c
// 0x125BF4ABFC536B09
bool IS_POINT_ON_ROAD(Vector3 vPos, Vehicle vehicle);
```

```
VehicleIndex is only used for Debug Drawing

Returns true if the position is within any road extremes, false otherwise Don't use too often, this is moderately expensive
```
