---
ns: TASK
aliases: ["0x23083260dec3a551"]
---
## ADD_PATROL_ROUTE_LINK

```c
// 0x23083260DEC3A551
void ADD_PATROL_ROUTE_LINK(int NodeId2);
```

Links two patrol nodes together.

A Node can have a maximum of 4 links. The direction of the link is the order passed in. e.g NodeA, NodeB passed in that order will will go to from A to B

