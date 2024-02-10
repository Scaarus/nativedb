---
ns: MISC
aliases: ["0xdd9b9b385aac7f5b"]
---
## CLEAR_AREA_OF_OBJECTS

```c
// 0xDD9B9B385AAC7F5B
void CLEAR_AREA_OF_OBJECTS(Vector3 CentrePosition, float Radius, int controlFlags);
```

```
Clears all non-mission objects within the defined sphere.

Possible values for controlFlags:
| Index | Name |
| --- | --- |
| 1 | Broadcast |
| 2 | Force |
| 4 | Include Doors |
| 8 | Include Objwithbrains |
| 16 | Exclude Ladders |
```
