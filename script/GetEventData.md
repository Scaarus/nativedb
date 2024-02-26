---
ns: SCRIPT
aliases: ["0x2902843fcd2b2d79"]
---
## GET_EVENT_DATA

```c
// 0x2902843FCD2B2D79
bool GET_EVENT_DATA(int eventQueue, int eventIndex, Any* data, int dataSize);
```

Retrieves data from the event. One of the structures defined about is passed in and filled out.

## eventQueue Values:
| Value | Name |
| --- | --- |
| 0 | Ai |
| 1 | Network |
| 2 | Errors |

