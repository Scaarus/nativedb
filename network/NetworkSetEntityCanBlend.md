---
ns: NETWORK
aliases: ["0xd830567d88a1e873"]
---
## NETWORK_SET_ENTITY_CAN_BLEND

```c
// 0xD830567D88A1E873
void NETWORK_SET_ENTITY_CAN_BLEND(Entity entity, bool CanBlend);
```

Sets whether this script entity can use the network blender to smooth position updates from the controlling machine. An example where you may want to disable this would be for an object that will be moved is several small warps, such as a golf player moving between stroke positions

