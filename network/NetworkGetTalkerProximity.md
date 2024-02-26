---
ns: NETWORK
aliases: ["0x84f0f13120b4e098"]
---
## NETWORK_GET_TALKER_PROXIMITY

```c
// 0x84F0F13120B4E098
float NETWORK_GET_TALKER_PROXIMITY();
```

Sets the distance threshold that determines how close a player must be before we can chat with him. This does not account for height. That can be set with NETWORK_SET_TALKER_PROXIMITY_HEIGHT below
0.0 implies no threshold and we can chat regardless of distance

