---
ns: TASK
aliases: ["0x8edf950167586b7c"]
---
## ADD_PATROL_ROUTE_NODE

```c
// 0x8EDF950167586B7C
void ADD_PATROL_ROUTE_NODE(string NodeType, Vector3 vNodePosition, Vector3 NodeLookAtPos, int Duration);
```

Adds a patrol route node. Moreinfo..

This can only be called once [OPEN_PATROL_ROUTE](#_0xA36BFB5EE89F3D82) has been called. There cane be a maximum of 16 nodes per route.


## Parameters
* **NodeType**: Taken from the following list. "WORLD_HUMAN_GUARD_STAND", "WORLD_HUMAN_SMOKING"
* **vNodePosition**: Position of the node
* **NodeLookAtPos**: This is the position in world coords where the ped will look at. Set this to zero to make the ped look at nothing.
* **Duration**: The time the ped will spend at the node.
