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
| 35 | Back Left Back Left |
| 36 | Back Right Back Right |
| 37 | Extra Left 1 |
| 38 | Extra Right 1 |
| 39 | Extra Left 2 |
| 40 | Extra Right 2 |
| 41 | Extra Left 3 |
| 42 | Extra Right 3 |


Command to check if the direct access entry point for a seat is clear (ped can enter/exit). This is quite expensive, So don't call it too often!


## Parameters
* **ped**: 
* **vehicle**: 
* **Seat**: 
* **CheckSide**: some vehicle seats can be entered from two sides (e.g. bike / jetski), if set to true, this checks the entry point corresponding to the LeftSide (set to FALSE to check the right side entry)
* **LeftSide**: 
