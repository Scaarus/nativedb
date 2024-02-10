---
ns: OBJECT
aliases: ["0xf82d8f1926a02c3d"]
---
## SET_STATE_OF_CLOSEST_DOOR_OF_TYPE

```c
// 0xF82D8F1926A02C3D
void SET_STATE_OF_CLOSEST_DOOR_OF_TYPE(Hash modelHash, Vector3 vecPos, bool LockState, float fOpenRatio, bool RemoveSpring);
```

Sest the state of the closest door of type.

Open

To open and shut a door smoothly call every frame with bLockState=false as you increasedecrease the openshut ratio In your script tidyup you should reset the door to bLockState = false, fOpenRatio = 0.0 to release the door. Unless you specifically want the door to remain locked for ever more. Get door position using helper widget: Rag Widgets -> Objects -> Show Door Info

