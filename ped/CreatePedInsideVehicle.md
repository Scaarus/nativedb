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
| 34 | Player2 Franklin |
| 35 | Player Network Player Controlled Over The Network (Not By This Machine) |
| 36 | Player Unused Trevor |
| 37 | Civmale |
| 38 | Civfemale |
| 39 | Cop |
| 40 | Gang1 |
| 41 | Gang2 |
| 42 | Gang3 |
| 43 | Gang4 |
| 44 | Gang5 |
| 45 | Gang6 |
| 46 | Gang7 |
| 47 | Gang8 |
| 48 | Gang9 |
| 49 | Gang10 |
| 50 | Gang Chinese Japanese |
| 51 | Gang Puerto Rican |
| 52 | Dealer |
| 53 | Medic |
| 54 | Fire |
| 55 | Criminal |
| 56 | Bum |
| 57 | Prostitute |
| 58 | Special |
| 59 | Mission |
| 60 | Swat |
| 61 | Animal |
| 62 | Army |
| 63 | Last Pedtype |


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


VEHICLE_SEAT enum is in generic.sch

If any_seat_is passed in the command will assert.


## Parameters
* **vehicle**: 
* **PedType**: 
* **modelHash**: 
* **Seat**: 
* **RegisterAsNetworkObject**: The new object will be created and synced on other machines if a network game is running
* **ScriptHostObject**: If true, this object has been created by the host portion of a network script and is vital to that
