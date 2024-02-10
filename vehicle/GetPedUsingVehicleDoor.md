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

## DoorNumber Values:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Front Left |
| 60 | Front Right |
| 61 | Rear Left |
| 62 | Rear Right |
| 63 | Bonnet |
| 64 | Boot |


SC_DOOR_LIST is in commands_vehicle.sch

