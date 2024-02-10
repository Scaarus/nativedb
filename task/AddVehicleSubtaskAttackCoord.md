---
ns: TASK
aliases: ["0x5cf0d8f9bba0dd75"]
---
## ADD_VEHICLE_SUBTASK_ATTACK_COORD

```c
// 0x5CF0D8F9BBA0DD75
void ADD_VEHICLE_SUBTASK_ATTACK_COORD(Ped ped, Vector3 vPosition);
```

Will append an attacking subtask to a previously given driving task. This can be used directly with a ped or in a sequence in the following commands: TASK_HELI_MISSION TASK_VEHICLE_DRIVE_TO_COORD TASK_VEHICLE_MISSION TASK_VEHICLE_MISSION_PED_TARGET TASK_VEHICLE_MISSION_COORS_TARGET SEE ALSO ADD_VEHICLE_SUBTASK_ATTACK_PED

Used as follows: TASK_VEHICLE_MISSION(Ped, params...) ADD_VEHICLE_SUBTASK_ATTACK_COORD(Ped, OtherPed) - will update the above task to include this subtask OR OPEN_SEQUENCE_TASK (SEQ) TASK_FLUSH_ROUTE() TASK_EXTEND_ROUTE(<< -17.30, -6.60, 1.19>> ) TASK_EXTEND_ROUTE(<<-16.69, 12.23, 1.19 >> ) TASK_EXTEND_ROUTE(<<12.18, 12.76, 1.19 >> ) TASK_EXTEND_ROUTE(<<13.37, -14.18, 1.19 >> ) TASK_DRIVE_POINT_ROUTE (NULL, veh, 1.0 ) ADD_VEHICLE_SUBTASK_ATTACK_PED(NULL, OtherPed) SET_SEQUENCE_TO_REPEAT(seq, REPEAT_FOREVER) CLOSE_SEQUENCE_TASK(SEQ)
