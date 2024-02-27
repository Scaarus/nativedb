---
ns: CAMERA
aliases: ["0x5d96cfb59da076a0"]
---
## TRIGGER_VEHICLE_PART_BROKEN_CAMERA_SHAKE

```c
// 0x5D96CFB59DA076A0
void TRIGGER_VEHICLE_PART_BROKEN_CAMERA_SHAKE(Entity entity, int vehiclePart, float amplitude);
```

trigger a camera shake bespokely tuned to match the the specified vehicle part position relative to the camera.


## Parameters
* **entity**: 
* **vehiclePart**: the vehicle part ID (needs to match the eHierarchyId enum)
* **amplitude**: the amplitude of the shake (1.0 is default, between 0.0 and 1.0 will scale down the shake strength, above 1.0 will increase it) (Default value: `1`)
