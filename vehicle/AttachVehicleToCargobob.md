---
ns: VEHICLE
aliases: ["0x4127f1d84e347769"]
---
## ATTACH_VEHICLE_TO_CARGOBOB

```c
// 0x4127F1D84E347769
void ATTACH_VEHICLE_TO_CARGOBOB(Vehicle vehicle, Vehicle vehicle, int VehicleBoneIndex, Vector3 VehicleAttachPointOffset);
```

Attaches a vehicle to a cargobob at a bone with an offset from that bone, use -1 to do an offset against the whole vehicle This does not reposition the vehicles, please try and position the vehicle around 0.5m under the cargobob

Attaches a vehicle to a tow truck

