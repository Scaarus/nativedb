---
ns: NETWORK
aliases: ["0xcf3a965906452031"]
---
## GET_NUM_RESERVED_MISSION_VEHICLES

```c
// 0xCF3A965906452031
int GET_NUM_RESERVED_MISSION_VEHICLES(bool ForAllScripts, int reservationType);
```

## Values for `reservationType`:
| Value | Name |
| --- | --- |
| 0 | All |
| 1 | Local Only |
| 2 | Global Only |


## Parameters
* **ForAllScripts**: if true, returns the totla number of reservations for all running scripts, if false, it returns the reservation for this script (Default value: `False`)
* **reservationType**: specifies whether to return the total reservations, local-only reservations, or global-only reservations (Default value: `All`)
