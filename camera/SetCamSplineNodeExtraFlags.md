---
ns: CAMERA
aliases: ["0x7bf1a54ae67ac070"]
---
## SET_CAM_SPLINE_NODE_EXTRA_FLAGS

```c
// 0x7BF1A54AE67AC070
void SET_CAM_SPLINE_NODE_EXTRA_FLAGS(Camera camera, int NodeIndex, int Flags);
```

```
Set/Clear additional spline node options.

Possible values for Flags:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Linear |
| 2 | Cut |
| 4 | Pause |
| 8 | Level |


Nodes must be setup first, then the extra flags can be modified.
```
