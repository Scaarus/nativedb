---
ns: OBJECT
aliases: ["0x2eaf1fdb2fb55698"]
---
## CREATE_PORTABLE_PICKUP

```c
// 0x2EAF1FDB2FB55698
Object CREATE_PORTABLE_PICKUP(Vector3 NewPosition, bool SnapToGround, Hash modelHash);
```

This creates a pickup object that persists and is carried when collected and can be attached to peds, etc. You can only call this for pickups that are set up to be portable in the pickups.meta data file. The OBJECT_INDEX that is returned can be used like any other object.


## Parameters
* **NewPosition**: World Coordinates of the pickup
* **SnapToGround**: When created the pickup will be placed on the ground correctly CustomModel If set this model will be used for the pickup instead of the default one bNetwork If true, the pickup will be synced across the network. If false, it won't appear on other machines (Default value: `True`)
* **modelHash**: (Default value: `0`)
