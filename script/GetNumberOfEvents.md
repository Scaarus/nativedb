---
ns: SCRIPT
aliases: ["0x5f92a689a06620aa"]
---
## GET_NUMBER_OF_EVENTS

```c
// 0x5F92A689A06620AA
int GET_NUMBER_OF_EVENTS(int eventQueue);
```

Returns the number of events in the given script queue.

## eventQueue Values:
| Value | Name |
| --- | --- |
| 0 | SCRIPT_EVENT_QUEUE_AI |
| 1 | SCRIPT_EVENT_QUEUE_NETWORK |
| 2 | SCRIPT_EVENT_QUEUE_ERRORS |
| 3 | NUM_SCRIPT_EVENT_QUEUES |

