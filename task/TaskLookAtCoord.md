---
ns: TASK
aliases: ["0x6fa46612594f7973"]
---
## TASK_LOOK_AT_COORD

```c
// 0x6FA46612594F7973
void TASK_LOOK_AT_COORD(Ped ped, Vector3 Position, int LookFlags, int priority);
```

Gives the ped a look at coord task.

## LookFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Slow Turn Rate |
| 2 | Fast Turn Rate |
| 4 | Extend Yaw Limit |
| 8 | Extend Pitch Limit |
| 16 | Widest Yaw Limit |
| 32 | Widest Pitch Limit |
| 64 | Narrow Yaw Limit |
| 128 | Narrow Pitch Limit |
| 256 | Narrowest Yaw Limit |
| 512 | Narrowest Pitch Limit |
| 1024 | Use Torso |
| 2048 | While Not In Fov |
| 4096 | Use Camera Focus |
| 8192 | Use Eyes Only |
| 16384 | Use Look Dir |
| 32768 | From Script |
| 65536 | Use Ref Dir Absolute |


## priority Values:
| Value | Name |
| --- | --- |
| 0 | Very Low |
| 1 | Low |
| 2 | Medium |
| 3 | High |
| 4 | Very High |


If LookTime is -1 the ped will perform the task forever. The optional flags parameter is made by combining any of the following flags from commands_task.sch.


## Parameters
* **ped**: 
* **Position**: 
* **LookFlags**: (Default value: `Default`)
* **priority**: (Default value: `Medium`)
