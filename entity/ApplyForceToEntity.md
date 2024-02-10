---
ns: ENTITY
aliases: ["0xc5f68be9613e2d18"]
---
## APPLY_FORCE_TO_ENTITY

```c
// 0xC5F68BE9613E2D18
void APPLY_FORCE_TO_ENTITY(Entity entity, int ApplyType, Vector3 vForce, Vector3 vOffset, int Component, bool LocalForce, bool LocalOffset, bool ScaleByMass, bool triggerAudio, bool ScaleByTimeWarp);
```

```
Apply a force to an entity.

Possible values for ApplyType:
| Index | Name |
| --- | --- |
| 0 | Force |
| 1 | Impulse Caution A Single Impact Applied At A Point In Time, Will Produce A Step Change In Velocity. If Applied Continuously Will Produce An Acceleration That Is Dependant On Frame Rate And May Also Break The Physics Engine, I.E. Please Do |
| 2 | External Force Same As A Normal Force But Applied As If It Was An External Push To The Object, Through The Breaking System. This Means That Breakable Objects Will Break Apart Due To The Force You'Re Applying. |
| 3 | External Impulse Ditto, A Nomal Impulse Plus Breaking. |
| 4 | Torque Angular Equivalent Of Force, Causes Continuous Angular Acceleration Independent Of Framerate |
| 5 | Angular Impulse Angular Equivalent Of Impulse, Causes Instantaneous Change In Angular Velocity |


APPLY_FORCE_TYPE see enum Vector force to be applied
```

## Parameters
* **entity**: 
* **ApplyType**: 
* **vForce**: 
* **vOffset**: Offset from centre of entity at which to apply force
* **Component**: Component of the entity to apply the force
* **LocalForce**: Specifies whether the force vector passed in is in local or world coordinates. Local coordinates (TRUE) means the force will get automatically transformed into world space before being applied.
* **LocalOffset**: Specifies whether the offset passed in is in local or world coordinates.
* **ScaleByMass**: Specifies whether to scale the force by mass. TRUE force will be multiplied by mass, ie Force passed in is in fact an acceleration rate in ms*s (force) or velocity change in ms(impulse) FALSE force will be applied directly and it's effect will depend on the mass of the object, ie Force passed in is a proper force in Newtons (force) or a step change in momentum kg*ms (impulse) In other words, scaling by mass is probably easier in most
* **triggerAudio**: 
* **ScaleByTimeWarp**: 
