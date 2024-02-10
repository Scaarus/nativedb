---
ns: ENTITY
aliases: ["0x57c5db656185eac4"]
---
## SET_ENTITY_TRAFFICLIGHT_OVERRIDE

```c
// 0x57C5DB656185EAC4
void SET_ENTITY_TRAFFICLIGHT_OVERRIDE(Entity entity, int overrideMode);
```

## overrideMode Values:
| Value | Name |
| --- | --- |
| 0 | Red |
| 1 | Amber |
| 2 | Green |
| 3 | None |


Use only on traffic lights entitys

Override the state of a traffic light to red, amber, green. or none.

