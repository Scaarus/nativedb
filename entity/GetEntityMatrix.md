---
ns: ENTITY
aliases: ["0xecb2fc7235a7d137"]
---
## GET_ENTITY_MATRIX

```c
// 0xECB2FC7235A7D137
void GET_ENTITY_MATRIX(Entity entity, Vector3 vFront, Vector3 vSide, Vector3 vUp, Vector3 vPos);
```

Fills out the given vectors with the components of the entity's world transformation matrix. This effectively gives you the forwards, right hand and up unit direction vectors as well as the entity's position


## Parameters
* **entity**: 
* **vFront**: where to store the entity's front vector
* **vSide**: where to store the entity's side (right hand) vector
* **vUp**: where to store the entity's up vector
* **vPos**: the entity's position
