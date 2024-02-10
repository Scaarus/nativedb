---
ns: WATER
aliases: ["0xf6829842c06ae524"]
---
## GET_WATER_HEIGHT

```c
// 0xF6829842C06AE524
bool GET_WATER_HEIGHT(Vector3 Pos, float Height);
```

Gets the height of the water below the position including the waves.

This command takes the waves into account so the result may be different depending on the exact frame of calling.

