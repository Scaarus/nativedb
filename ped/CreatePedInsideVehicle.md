---
ns: PED
aliases: ["0x7dd959874c1fd534"]
---
## CREATE_PED_INSIDE_VEHICLE

```c
// 0x7DD959874C1FD534
Ped CREATE_PED_INSIDE_VEHICLE(Vehicle vehicle, int PedType, Hash modelHash, int Seat, bool RegisterAsNetworkObject, bool ScriptHostObject);
```

Creates a ped inside at seat number.

## PedType Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Player1 |
| 1 | Player2 (Franklin) |
| 2 | Player Network (Player Controlled Over The Network (Not By This Machine)) |
| 3 | Player Unused (Trevor) |
| 4 | Civmale |
| 5 | Civfemale |
| 6 | Cop |
| 7 | Gang1 |
| 8 | Gang2 |
| 9 | Gang3 |
| 10 | Gang4 |
| 11 | Gang5 |
| 12 | Gang6 |
| 13 | Gang7 |
| 14 | Gang8 |
| 15 | Gang9 |
| 16 | Gang10 |
| 17 | Gang Chinese Japanese |
| 18 | Gang Puerto Rican |
| 19 | Dealer |
| 20 | Medic |
| 21 | Fire |
| 22 | Criminal |
| 23 | Bum |
| 24 | Prostitute |
| 25 | Special |
| 26 | Mission |
| 27 | Swat |
| 28 | Animal |
| 29 | Army |
| 30 | Last Pedtype |


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


VEHICLE_SEAT enum is in generic.sch

If any_seat_is passed in the command will assert.


## Parameters
* **vehicle**: 
* **PedType**: 
* **modelHash**: 
* **Seat**: (Default value: `Driver`)
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running (Default value: `True`)
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that (Default value: `True`)
