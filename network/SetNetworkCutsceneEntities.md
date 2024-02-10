---
ns: NETWORK
aliases: ["0xaaa553e7dd28a457"]
---
## SET_NETWORK_CUTSCENE_ENTITIES

```c
// 0xAAA553E7DD28A457
void SET_NETWORK_CUTSCENE_ENTITIES(bool Network);
```

If this called with TRUE, any entities subsequently created during a cutscene will be networked as normal. By default, entities created during a cutscene are not networked as they are only needed locally for the cutscene.

