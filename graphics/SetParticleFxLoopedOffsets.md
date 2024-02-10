---
ns: GRAPHICS
aliases: ["0xf7ddebec43483c43"]
---
## SET_PARTICLE_FX_LOOPED_OFFSETS

```c
// 0xF7DDEBEC43483C43
void SET_PARTICLE_FX_LOOPED_OFFSETS(int ptfxId, Vector3 position, Vector3 vecRotation);
```

```
Update the position and/or rotation offsets of a previously started looped particle effect. More info

PTFX_ID

If the particle effect is attached to an entity (ped, vehicle or object) then the new position is an offset from that entity. If the particle effect is not attached to an entity (ped, vehicle or object) then the new position is a world position.
```

## Parameters
* **ptfxId**: the id of the started particle effect to update VECTOR
* **position**: the new position of the particle effect VECTOR
* **vecRotation**: 
