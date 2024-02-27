---
ns: VEHICLE
aliases: ["0x639431e895b9aa57"]
---
## IS_ENTRY_POINT_FOR_SEAT_CLEAR

```c
// 0x639431E895B9AA57
bool IS_ENTRY_POINT_FOR_SEAT_CLEAR(Ped ped, Vehicle vehicle, int Seat, bool CheckSide, bool LeftSide);
```

## Seat Values:
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


Command to check if the direct access entry point for a seat is clear (ped can enter/exit). This is quite expensive, So don't call it too often!


## Parameters
* **ped**: 
* **vehicle**: 
* **Seat**: 
* **CheckSide**: some vehicle seats can be entered from two sides (e.g. bike / jetski), if set to true, this checks the entry point corresponding to the LeftSide (set to FALSE to check the right side entry) (Default value: `False`)
* **LeftSide**: (Default value: `False`)
