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
| 0 | Parallel |
| 1 | Perpendicular Nose In |
| 2 | Perpendicular Back In |
| 3 | Pull Over |
| 4 | Leave Parallel Space |
| 5 | Back Out Perpendicular Space |
| 6 | Passenger Exit |
| 7 | Pull Over Immediate |


## Parameters
* **ped**: 
* **vehicle**: 
* **ParkingSpaceCoords**: The center of the space.
* **DirectionDegrees**: Heading of the parking space. Can be either positive or negative direction--how the car enters the space is determined by the PARK_TYPE
* **ParkType**: Style of parking.
* **ToleranceDegrees**: If the vehicle's heading isn't within this amount of the Direction param, the vehicle will back up and try to straighten itself out
* **KeepLightsOn**: If true, keep the lights on after parking
