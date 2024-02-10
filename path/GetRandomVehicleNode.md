---
ns: PATH
aliases: ["0x93e0db8440b73a7d"]
---
## GET_RANDOM_VEHICLE_NODE

```c
// 0x93E0DB8440B73A7D
bool GET_RANDOM_VEHICLE_NODE(float radius, int MinLanes, bool AvoidDeadEnds, bool AvoidHighways, Vector3 vecReturn, int NodeAddress);
```

Will return a random node to satisfy the specified conditions.

. Every time this command is called 64 nodes are batched (so you won't get the same node twice in the first 64 calls) Once the node has been returned and perhaps sent to a client the coordinates to spawn a car can be found using GET_SPAWN_COORDINATES_FOR_CAR_NODE

