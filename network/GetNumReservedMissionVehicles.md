---
ns: NETWORK
aliases: ["0xcf3a965906452031"]
---
## GET_NUM_RESERVED_MISSION_VEHICLES

```c
// 0xCF3A965906452031
int GET_NUM_RESERVED_MISSION_VEHICLES(bool ForAllScripts, int reservationType);
```

```
Possible values for reservationType:
| Index | Name |
| --- | --- |
| 0 | All |
| 236 | Local Only |
| 237 | Global Only |
```

## Parameters
* **ForAllScripts**: if true, returns the totla number of reservations for all running scripts, if false, it returns the reservation for this script
* **reservationType**: specifies whether to return the total reservations, local-only reservations, or global-only reservations
