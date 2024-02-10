---
ns: NETWORK
aliases: ["0xcbf12d65f95ad686"]
---
## NETWORK_SET_TALKER_PROXIMITY

```c
// 0xCBF12D65F95AD686
void NETWORK_SET_TALKER_PROXIMITY(float distance);
```

Sets the distance threshold that determines how close a player must be before we can chat with him. This does not account for height. That can be set with NETWORK_SET_TALKER_PROXIMITY_HEIGHT below

