---
ns: PATH
aliases: ["0xd268dae911420879"]
---
## LOAD_ALL_PATH_NODES

```c
// 0xD268DAE911420879
bool LOAD_ALL_PATH_NODES(bool Set);
```

Loads/unloads all path nodes on the map.

The return value becomes true when this has actually happened. If called with false the nodes are released. In this case the return value is irrelevant.

