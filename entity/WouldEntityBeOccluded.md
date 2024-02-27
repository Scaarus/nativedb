---
ns: ENTITY
aliases: ["0xee5d2a122e09ec42"]
---
## WOULD_ENTITY_BE_OCCLUDED

```c
// 0xEE5D2A122E09EC42
bool WOULD_ENTITY_BE_OCCLUDED(Vector3 Coords, bool AssertIfModelIsntLoaded);
```

Checks whether an entity created with the given model and position would be visible with the current camera


## Parameters
* **Coords**: 
* **AssertIfModelIsntLoaded**: If the model isn't loaded and bAssertIfModelIsntLoaded is TRUE then the game will assert and return FALSE. If the model isn't loaded and bAssertIfModelIsntLoaded is FALSE then the game will return FALSE (without asserting). (Default value: `True`)
