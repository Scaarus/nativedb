---
ns: ENTITY
aliases: ["0x8339643499d1222e"]
---
## SET_ENTITY_ANGULAR_VELOCITY

```c
// 0x8339643499D1222E
void SET_ENTITY_ANGULAR_VELOCITY(Entity entity, Vector3 VelocityComponentt);
```

Sets the entity's angular velocity.

The ang velocity componets should be less than 2.0f * PI

The ang speeds are measured in degrees ( in radians ) per frame.

