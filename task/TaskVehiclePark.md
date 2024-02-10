---
ns: TASK
aliases: ["0x0f3e34e968ea374e"]
---
## TASK_VEHICLE_PARK

```c
// 0x0F3E34E968EA374E
void TASK_VEHICLE_PARK(Ped ped, Vehicle vehicle, Vector3 ParkingSpaceCoords, float DirectionDegrees, int ParkType, float ToleranceDegrees, bool KeepLightsOn);
```

Gives the vehicle a task to park in the specified manner

## ParkType Values:
| Value | Name |
| --- | --- |
| 283 | Parallel |
| 284 | Perpendicular Nose In |
| 285 | Perpendicular Back In |
| 286 | Pull Over |
| 287 | Leave Parallel Space |
| 288 | Back Out Perpendicular Space |
| 289 | Passenger Exit |
| 290 | Pull Over Immediate |


## Parameters
* **ped**: 
* **vehicle**: 
* **ParkingSpaceCoords**: The center of the space.
* **DirectionDegrees**: Heading of the parking space. Can be either positive or negative direction--how the car enters the space is determined by the PARK_TYPE
* **ParkType**: Style of parking.
* **ToleranceDegrees**: If the vehicle's heading isn't within this amount of the Direction param, the vehicle will back up and try to straighten itself out
* **KeepLightsOn**: If true, keep the lights on after parking
