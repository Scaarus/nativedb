---
ns: PATH
aliases: ["0x07fb139b592fa687"]
---
## REQUEST_PATH_NODES_IN_AREA_THIS_FRAME

```c
// 0x07FB139B592FA687
bool REQUEST_PATH_NODES_IN_AREA_THIS_FRAME(float MinX, float MinY, float MaxX, float MaxY);
```

When this command is called, the path nodes in the given region be requested by streaming that frame. This does not guarantee that the nodes will be loaded this frame, you should keep calling this command for as long as you wish nodes to be present in the given area, and you should call [`ARE_NODES_LOADED_FOR_AREA`](#_0xF7B79A50B905A30D) to check for when they have streamed in. If you stop calling this command, the nodes may be streamed out again at any time.

