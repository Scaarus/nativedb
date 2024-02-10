---
ns: PATH
aliases: ["0xf7b79a50b905a30d"]
---
## ARE_NODES_LOADED_FOR_AREA

```c
// 0xF7B79A50B905A30D
bool ARE_NODES_LOADED_FOR_AREA(float MinX, float MinY, float MaxX, float MaxY);
```

```
~> Streaming commands

Returns true if path nodes are loaded for the region specified Unlike LOAD_ALL_PATH_NODES(), we don't return a bool for the initial request, so use this function to query if the nodes you want are loaded
```
