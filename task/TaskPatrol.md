---
ns: TASK
aliases: ["0xbda5df49d080fe4e"]
---
## TASK_PATROL

```c
// 0xBDA5DF49D080FE4E
void TASK_PATROL(Ped ped, string RouteName, int PedAlertState, bool CanChatToPeds, bool CanUseHeadLookAtAlongRoute);
```

Adds the completed patrol route.

## PedAlertState Values:
| Value | Name |
| --- | --- |
| 0 | Casual |
| 1 | Alert |


This can only be called once a valid a ptrol route has been added.


## Parameters
* **ped**: 
* **RouteName**: 
* **PedAlertState**: 
* **CanChatToPeds**: (Default value: `False`)
* **CanUseHeadLookAtAlongRoute**: (Default value: `True`)
