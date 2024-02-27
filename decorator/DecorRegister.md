---
ns: DECORATOR
aliases: ["0x9fd90732f56403ce"]
---
## DECOR_REGISTER

```c
// 0x9FD90732F56403CE
void DECOR_REGISTER(string decoratorName, int type);
```

Register a decorator to be used as a specific type

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
