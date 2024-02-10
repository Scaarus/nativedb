---
ns: NETWORK
aliases: ["0x1f13d5ae5cb17e17"]
---
## GET_NUM_RESERVED_MISSION_PEDS

```c
// 0x1F13D5AE5CB17E17
int GET_NUM_RESERVED_MISSION_PEDS(bool ForAllScripts, int reservationType);
```

## reservationType Values:
| Value | Name |
| --- | --- |
| 0 | All |
| 236 | Local Only |
| 237 | Global Only |


## Parameters
* **ForAllScripts**: if true, returns the totla number of reservations for all running scripts, if false, it returns the reservation for this script
* **reservationType**: specifies whether to return the total reservations, local-only reservations, or global-only reservations