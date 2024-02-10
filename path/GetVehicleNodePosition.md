---
ns: PATH
aliases: ["0x703123e5e7d429c2"]
---
## GET_VEHICLE_NODE_POSITION

```c
// 0x703123E5E7D429C2
void GET_VEHICLE_NODE_POSITION(Vector3 NodePosition);
```

Resolves a node id to a position

As GET_NTH_CLOSEST_VEHICLE_NODE... but returns a node index. This node index MUST be used within this frame as it's validity is not guaranteed outside.

