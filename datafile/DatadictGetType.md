---
ns: DATAFILE
aliases: ["0x031c55ed33227371"]
---
## DATADICT_GET_TYPE

```c
// 0x031C55ED33227371
datafile_type DATADICT_GET_TYPE(Any* dict, string name);
```

```
Gets the data type for the data corresponding to a name in the dictionary

Possible return values:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Bool |
| 2 | Int |
| 3 | Float |
| 4 | String |
| 5 | Vec3 |
| 6 | Dict |
| 7 | Array |
```

## Parameters
* **dict**: The dictionary object
* **name**: The name of the data item
