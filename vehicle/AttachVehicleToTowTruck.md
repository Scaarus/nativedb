---
ns: VEHICLE
aliases: ["0x29a16f8d621c4508"]
---
## ATTACH_VEHICLE_TO_TOW_TRUCK

```c
// 0x29A16F8D621C4508
void ATTACH_VEHICLE_TO_TOW_TRUCK(Vehicle vehicle, Vehicle vehicle, int VehicleBoneIndex, Vector3 VehicleAttachPointOffset);
```

Attaches a vehicle to a tow truck at a bone with an offset from that bone, use -1 to do an offset against the whole vehicle This does not reposition the vehicles, please try and position the vehicle around 0.5m behind the truck

Attaches a vehicle to a tow truck

