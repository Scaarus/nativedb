---
ns: VEHICLE
aliases: ["0xa1dd82f3ccf9a01e"]
---
## ATTACH_ENTITY_TO_CARGOBOB

```c
// 0xA1DD82F3CCF9A01E
void ATTACH_ENTITY_TO_CARGOBOB(Vehicle vehicle, Entity entity, int EntityBoneIndex, Vector3 VehicleAttachPointOffset);
```

```
Attaches an entity to a cargobob at a bone with an offset from that bone, use -1 to do an offset against the whole vehicle This does not reposition the entity, please try and position the entity around 0.5m under the cargobob

Attaches an entity to a cargobob
```
