---
ns: TASK
aliases: ["0xf7f9dcca89e7505b"]
---
## TASK_PLANE_GOTO_PRECISE_VTOL

```c
// 0xF7F9DCCA89E7505B
void TASK_PLANE_GOTO_PRECISE_VTOL(Ped ped, Vehicle vehicle, Vector3 TargetCoords, int FlightHeight, int MinHeightAboveTerrain, bool UseDesiredOrientation, float DesiredOrientation, bool AutoPilot);
```

Exposes more params than [`TASK_VEHICLE_MISSION`](#_0x659427E0EF36BCDE) allows, allows for greater control of VTOL planes.

bAutoPilot will apply the plane goto task directly to the vehicle, and apply some flags to allow this task to run with no driver

Tells a plane with VTOL (like the Vulkan) to move precisely throughout the world. Will fail for other vehicles


## Parameters
* **ped**: 
* **vehicle**: 
* **TargetCoords**: 
* **FlightHeight**: (Default value: `30`)
* **MinHeightAboveTerrain**: (Default value: `20`)
* **UseDesiredOrientation**: (Default value: `False`)
* **DesiredOrientation**: (Default value: `0`)
* **AutoPilot**: (Default value: `False`)
