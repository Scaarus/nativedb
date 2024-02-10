---
ns: GRAPHICS
aliases: ["0x9b6e70c5ceef4eeb"]
---
## QUERY_MOVIE_MESH_SET_STATE

```c
// 0x9B6E70C5CEEF4EEB
moviemeshsetstate QUERY_MOVIE_MESH_SET_STATE(int id);
```

```
Queries the state of a mesh set

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Failed |
| 0 | Pending Load |
| 1 | Loaded |
| 2 | Ready |
| 3 | Pending Delete |
```
