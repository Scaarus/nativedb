---
ns: TASK
aliases: ["0x9a7d091411c5f684"]
---
## TASK_WARP_PED_INTO_VEHICLE

```c
// 0x9A7D091411C5F684
void TASK_WARP_PED_INTO_VEHICLE(Ped ped, int seat);
```

Can warp a ped into a vehicle using a task sequence.

## Values for `seat`:
| Value | Name |
| --- | --- |
| -2 | Any Passenger |
| -1 | Driver |
| 0 | Front Right |
| 1 | Back Left (Back Left) |
| 2 | Back Right (Back Right) |
| 3 | Extra Left 1 |
| 4 | Extra Right 1 |
| 5 | Extra Left 2 |
| 6 | Extra Right 2 |
| 7 | Extra Left 3 |
| 8 | Extra Right 3 |


## Parameters
* **ped**: 
* **seat**: (Default value: `Driver`)
