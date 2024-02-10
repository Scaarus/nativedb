---
ns: TASK
aliases: ["0xb4f47213df45a64c"]
---
## GET_TASK_MOVE_NETWORK_EVENT

```c
// 0xB4F47213DF45A64C
bool GET_TASK_MOVE_NETWORK_EVENT(Ped ped, string eventName);
```

Returns true if an event with the given name has just fired on the ped's script owned MoVE network Can be used to trigger creation of objects in script, etc

Allows script to recieve named events from a running MoVE network

