---
ns: VEHICLE
aliases: ["0x16b5e274bde402f8"]
---
## ATTACH_VEHICLE_ON_TO_TRAILER

```c
// 0x16B5E274BDE402F8
void ATTACH_VEHICLE_ON_TO_TRAILER(Vehicle vehicle, Vehicle vehicle, Vector3 FirstEntityOffset, Vector3 SecondEntityOffset, Vector3 vecRotation, float PhysicalStrength);
```

Attaches a vehicle on to the back of a trailer. This limits the mass of the vehicle put onto the trailer to reduce physics issues

