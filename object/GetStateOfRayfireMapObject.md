---
ns: OBJECT
aliases: ["0x899ba936634a322e"]
---
## GET_STATE_OF_RAYFIRE_MAP_OBJECT

```c
// 0x899BA936634A322E
ray_fire_map_object_state GET_STATE_OF_RAYFIRE_MAP_OBJECT(Rayfire rayfire);
```

```
Get the state of the rayfire map object.

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Init |
| 1 | Sync Starting |
| 2 | Starting |
| 3 | Start |
| 4 | Priming |
| 5 | Primed |
| 6 | Start Anim |
| 7 | Animating |
| 8 | Sync Ending |
| 9 | Ending |
| 10 | End |
| 11 | Reset |
| 12 | Pause |
| 13 | Resume |
| 14 | Priming Prelude |
| 15 | Abandon |
```
