---
ns: PHYSICS
aliases: ["0x3d95ec8b6d940ac3"]
---
## ATTACH_ENTITIES_TO_ROPE

```c
// 0x3D95EC8B6D940AC3
void ATTACH_ENTITIES_TO_ROPE(Entity entity, Entity entity, Vector3 worldPositionA, Vector3 worldPositionB, float ropeLength, int componentPartA, int componentPartB, string boneNamePartA, string boneNamePartB);
```

```
Attach two entities to a rope. Entities need to be physical.

Pass 0 to componentPartA and componentPartB if no parts exist or want to attach the rope to the main objectpart
```
