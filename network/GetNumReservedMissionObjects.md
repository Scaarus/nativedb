---
ns: NETWORK
aliases: ["0xaa81b5f10bc43ac2"]
---
## GET_NUM_RESERVED_MISSION_OBJECTS

```c
// 0xAA81B5F10BC43AC2
int GET_NUM_RESERVED_MISSION_OBJECTS(bool ForAllScripts, int reservationType);
```

## reservationType Values:
| Value | Name |
| --- | --- |
| 0 | All |
| 1 | Local Only |
| 2 | Global Only |


## Parameters
* **ForAllScripts**: if true, returns the totla number of reservations for all running scripts, if false, it returns the reservation for this script (Default value: `False`)
* **reservationType**: specifies whether to return the total reservations, local-only reservations, or global-only reservations (Default value: `All`)
