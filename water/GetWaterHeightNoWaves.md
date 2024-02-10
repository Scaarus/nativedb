---
ns: WATER
aliases: ["0x8ee6b53ce13a9794"]
---
## GET_WATER_HEIGHT_NO_WAVES

```c
// 0x8EE6B53CE13A9794
bool GET_WATER_HEIGHT_NO_WAVES(Vector3 Pos, float Height);
```

Gets the height of the water below the position excluding the waves.

This command does not take the waves into account so the result will be the same between different frames

