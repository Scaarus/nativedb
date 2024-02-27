---
ns: TASK
aliases: ["0xab13a5565480b6d9"]
---
## SET_EXPECTED_CLONE_NEXT_TASK_MOVE_NETWORK_STATE

```c
// 0xAB13A5565480B6D9
bool SET_EXPECTED_CLONE_NEXT_TASK_MOVE_NETWORK_STATE(Ped ped, string StateName);
```

To be used for particular move networks after [`REQUEST_TASK_MOVE_NETWORK_STATE_TRANSITION`](#_0xD01015C7316AE176) when the request will expect to cause the Move Network to automatically eventually progress to the queued MoVE state. Setting this syncs to remote machine and alerts the remote clone to scan for this state

