---
ns: PHYSICS
aliases: ["0xe832d760399eb220"]
---
## ADD_ROPE

```c
// 0xE832D760399EB220
Rope ADD_ROPE(Vector3 rot, float len, int ropeType, float initialLen, float minLen, float lengthChangeRate, bool ppuOnly, bool collisionOn, bool lockFromFront, float timeMultiplier, bool reakable, string materialName);
```

Creat rope and return rope's unique ID.

## ropeType Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Thin |
| 1 | Default |
| 2 | Default 32 |
| 3 | Default Wire |
| 4 | Thin Wire 32 |
| 5 | Reins |
| 6 | Thin4 |


## Parameters
* **rot**: 
* **len**: 
* **ropeType**: 
* **initialLen**: 
* **minLen**: (Default value: `0`)
* **lengthChangeRate**: (Default value: `0`)
* **ppuOnly**: (Default value: `False`)
* **collisionOn**: (Default value: `False`)
* **lockFromFront**: (Default value: `True`)
* **timeMultiplier**: (Default value: `1`)
* **reakable**: (Default value: `False`)
* **materialName**: (Default value: `Null`)
