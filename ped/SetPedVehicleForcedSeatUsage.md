---
ns: PED
aliases: ["0x952f06beecd775cc"]
---
## SET_PED_VEHICLE_FORCED_SEAT_USAGE

```c
// 0x952F06BEECD775CC
void SET_PED_VEHICLE_FORCED_SEAT_USAGE(Ped ped, Vehicle vehicle, int iSlot, int iFlags, int seat);
```

Force a ped to use front or rear seats for a particular vehicle, if no vehicle is specified, it is assumed this is to be applied for any vehicle this has the potential to cause conflicts with other slots, if wanting to apply a setting for all vehicles, script should call [`CLEAR_ALL_PED_VEHICLE_FORCED_SEAT_USAGE`](#_0xE6CA85E7259CE16B) beforehand

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


iSlot is an index into an array of config data for a particular vehicle max of 3 slots (0-2), iFlags is a bitset see enum VEHICLE_ENTRY_CONFIG_FLAGS


## Parameters
* **ped**: 
* **vehicle**: 
* **iSlot**: 
* **iFlags**: 
* **seat**: (Default value: `Any Passenger`)
