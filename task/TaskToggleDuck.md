---
ns: TASK
aliases: ["0xac96609b9995edf8"]
---
## TASK_TOGGLE_DUCK

```c
// 0xAC96609B9995EDF8
void TASK_TOGGLE_DUCK(Ped ped, int toggle);
```

Gives the task to set a ped duck state.

These are now mapped (as closely as possible) to firing patterns defined in commands_ped.sch Only PosNeg Y will work correctly, since pitch is limited and we cannot control roll directly Should be safe to use for perpendicular directions though Cover exit types This enum has to match the enum in script_tasks.h Keep in sync with eScriptAnimFlags in commands_task.cpp New blend duration defines - for use with [`TASK_SCRIPTED_ANIMATION`](#_0x126EF75F1E17ABE5) Keep in sync with CTaskScriptedAnimation::ePlayBackState (TaskScriptedAnimation.h) Keep in sync with CTaskScriptedAnimation::InitSlotData (TaskScriptedAnimation.h) Keep in sync with CTaskMoVEScripted::ScriptInitialParameters (TaskMoveScripted.h) Keep in sync with eLookAtPriority in IKManager.h ********************************************************************************************************* ENTER_EXIT_VEHICLE_FLAGS Set of flags to define the behaviour of the enter and exit vehicle tasks Specifies what components are attached at the end of a playing a attach anim Specifies the list of available move networks Scripted Gun Tasks Mobile Phone modes. Ensure this remains in sync with the "PhoneMode" enum in TaskMobilePhone.h. Used by [`TASK_VEHICLE_ESCORT`](#_0x0FA6E4B75F302400) ~> Movement commands

## Values for `toggle`:
| Value | Name |
| --- | --- |
| -1 | Auto |
| 0 | Off |
| 1 | On |

