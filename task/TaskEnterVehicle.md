---
ns: TASK
aliases: ["0xc20e50aa46d09ca8"]
---
## TASK_ENTER_VEHICLE

```c
// 0xC20E50AA46D09CA8
void TASK_ENTER_VEHICLE(Vehicle vehicle, int Time, int seat, float MoveBlendRatio, int iFlags, string OverridenClipSet);
```

Tells a ped to enter a vehicle.

## seat Values:
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


## iFlags Values:
| Value | Name |
| --- | --- |
| 1 | Resume If Interrupted |
| 2 | Warp Entry Point |
| 8 | Jack Anyone |
| 16 | Warp Ped |
| 64 | Dont Wait For Vehicle To Stop |
| 256 | Dont Close Door |
| 512 | Warp If Door Is Blocked |
| 4096 | Jump Out |
| 65536 | Dont Default Warp If Door Blocked |
| 131072 | Use Left Entry |
| 262144 | Use Right Entry |
| 524288 | Just Pull Ped Out |
| 1048576 | Block Seat Shuffling |
| 4194304 | Warp If Shuffle Link Is Blocked |
| 8388608 | Dont Jack Anyone |
| 16777216 | Wait For Entry Point To Be Clear |


If Time = -1 the ped will never warp into the vehicle. VEHICLE_SEAT is in generic.sch


## Parameters
* **vehicle**: 
* **Time**: 
* **seat**: (Default value: `Driver`)
* **MoveBlendRatio**: (Default value: `Pedmoveblendratio_Run`)
* **iFlags**: (Default value: `Resume If Interrupted`)
* **OverridenClipSet**: (Default value: `Null`)
