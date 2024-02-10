---
ns: NETWORK
aliases: ["0xde564951f95e09ed"]
---
## NETWORK_FADE_OUT_ENTITY

```c
// 0xDE564951F95E09ED
void NETWORK_FADE_OUT_ENTITY(Entity entity, bool Flash, bool Network);
```

```
Fades out the entity locally and remotely
```

## Parameters
* **entity**: 
* **Flash**: if true, the entity will flash during the fade, if false the entity will do a smooth fade
* **Network**: if true, the fade will be networked and appear on other machines
