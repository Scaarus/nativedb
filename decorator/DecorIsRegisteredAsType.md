---
ns: DECORATOR
aliases: ["0x4f14f9f870d6fbc8"]
---
## DECOR_IS_REGISTERED_AS_TYPE

```c
// 0x4F14F9F870D6FBC8
bool DECOR_IS_REGISTERED_AS_TYPE(string decoratorName, int type);
```

Query to see if a registered decorator is of an expected type

## Values for `type`:
| Value | Name |
| --- | --- |
| 0 | Unknown |
| 1 | Float |
| 2 | Bool |
| 3 | Int |
| 4 | String |
| 5 | Time |


## Parameters
* **decoratorName**: Name of the decorator
* **type**: expected type
