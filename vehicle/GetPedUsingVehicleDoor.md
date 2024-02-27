---
ns: VEHICLE
aliases: ["0x218297bf0cfd853b"]
---
## GET_PED_USING_VEHICLE_DOOR

```c
// 0x218297BF0CFD853B
Ped GET_PED_USING_VEHICLE_DOOR(Vehicle vehicle, int DoorNumber);
```

Gets the ped that current holds a door reservation for the requested vehicle door

## Values for `DoorNumber`:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 1 | Front Right |
| 2 | Rear Left |
| 3 | Rear Right |
| 4 | Bonnet |
| 5 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

