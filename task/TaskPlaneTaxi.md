---
ns: TASK
aliases: ["0x92c360b5f15d2302"]
---
## TASK_PLANE_TAXI

```c
// 0x92C360B5F15D2302
void TASK_PLANE_TAXI(Vehicle vehicle, Vector3 Position, float CruiseSpeed, float TargetReachedDist);
```

Gives plane a task to drive/taxi along the runway on the ground

VEHICLE_INDEX VehicleIndex (The actual plane that will be flown) FLOAT CruiseSpeed (in ms) FLOAT TargetReachedDist (distance (in meters) at which plane thinks it's arrived.)

