---
ns: TASK
aliases: ["0x2f8af0e82773a171"]
---
## TASK_DRIVE_BY

```c
// 0x2F8AF0E82773A171
void TASK_DRIVE_BY(Ped ped, Vehicle vehicle, Vector3 Position, float AbortRange, int FrequencyPercentage, bool PushUnderneathDrivingTaskIfDriving, int FiringPatternHash);
```

Tells a ped to driveby a coord, ped or vehicle.

## FiringPatternHash Values:
| Value | Name |
| --- | --- |
| -1857128337 | Burst Fire Heli |
| -1842093953 | Tampa Mortar |
| -957453492 | Full Auto |
| -753768974 | Burst Fire Driveby |
| -687903391 | Burst Fire |
| -490063247 | Slow Fire Tank |
| 445831135 | Short Bursts |
| 1122960381 | Burst Fire Micro |
| 1566631136 | Single Shot |
| 2055493265 | Delay Fire By One Sec |


The character can fire at a vehicle, coordinates or another character. At least one of TargetCharID and TargetVehicleID must be NULL. If there is a target character or vehicle then the target coordinates are used as an offset. If TargetCharID and TargetVehicleID are both NULL then the character will fire at the target coordinates. CharID and TargetCharID are both of type PED_INDEX TargetVehicleID is of type VEHICLE_INDEX AbortRangeFloat is the distance in metres from the target at which the task will be aborted. FireFrequencyPercentage should be between 0 (never shoot) and 100 (fire as fast as possible). bPushUnderneathDrivingTaskIfDriving If this is set it will allow the ped to continue driving whilst shooting. instead of interupting the driving task it will sit along side it. CLEAR_DRIVEBY_TASK_UNDERNEATH_DRIVING_TASK can be used to remove it FiringPatternHash allows you to set the firing pattern from a

