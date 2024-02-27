---
ns: NETWORK
aliases: ["0x1f13d5ae5cb17e17"]
---
## GET_NUM_RESERVED_MISSION_PEDS

```c
// 0x1F13D5AE5CB17E17
int GET_NUM_RESERVED_MISSION_PEDS(bool ForAllScripts, int reservationType);
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
