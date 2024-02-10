---
ns: CAMERA
aliases: ["0x8db3f12a02caef72"]
---
## ATTACH_CAM_TO_VEHICLE_BONE

```c
// 0x8DB3F12A02CAEF72
void ATTACH_CAM_TO_VEHICLE_BONE(Camera camera, Entity entity, int vehicleBoneIndex, bool hardAttachment, Vector3 vecRotationOffset, Vector3 vecPositionOffset, bool OffsetIsRelative);
```

Attaches a camera to a vehicle's bone.


## Parameters
* **camera**: 
* **entity**: 
* **vehicleBoneIndex**: The index of the vehicle bone to attach to.
* **hardAttachment**: if set to true, will fully attach the camera to the bone transform, otherwise only the position of the bone will be retained.
* **vecRotationOffset**: An additional rotational offset to be applied from the attach bone rotation (x=yaw, y=pitch, z=roll). This is only considered if hardAttachment is set to TRUE.
* **vecPositionOffset**: An additional offset to be applied from the attach position.
* **OffsetIsRelative**: If true, the offsets are applied relative to the transform of the attached vehicle (not the bone), rather than in world-space.
