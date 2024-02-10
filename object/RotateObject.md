---
ns: OBJECT
aliases: ["0xafe24e4d29249e4a"]
---
## ROTATE_OBJECT

```c
// 0xAFE24E4D29249E4A
bool ROTATE_OBJECT(float RotationStep, bool StopForCollision);
```

Rotates the object by RotationStep degrees each frame until it is at the TargetRotation

TargetRotation and RotationStep are both measured in degrees and should be between 0 and 360.

The object will always rotate in the direction that requires the least amount of movement. This command returns TRUE when the object is at the correct rotation. If StopForCollisionFlag is TRUE then the command will also return TRUE if the object has collided with a ped or vehicle.

