---
ns: DATAFILE
aliases: ["0x3a0014adb172a3c5"]
---
## DATAARRAY_GET_TYPE

```c
// 0x3A0014ADB172A3C5
datafile_type DATAARRAY_GET_TYPE(Any* arr, int index);
```

```
Gets the type of value stored a the specified index in an array

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
* **arr**: The array
* **index**: The index into the array
