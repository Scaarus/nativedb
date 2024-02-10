---
ns: PATH
aliases: ["0x16f46fb18c8009e4"]
---
## GET_POSITION_BY_SIDE_OF_ROAD

```c
// 0x16F46FB18C8009E4
bool GET_POSITION_BY_SIDE_OF_ROAD(int iDirection);
```

If the input node position is unsuitable, it will search 30m for a valid node.


## Parameters
* **iDirection**: should be a direction (0=forwards, 1=back, -1=doesn't matter)
