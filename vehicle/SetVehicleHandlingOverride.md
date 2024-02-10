---
ns: VEHICLE
aliases: ["0x645d663dc4b987af"]
---
## SET_VEHICLE_HANDLING_OVERRIDE

```c
// 0x645D663DC4B987AF
void SET_VEHICLE_HANDLING_OVERRIDE(Vehicle vehicle, int HandlingOverrideHash);
```

Overrides the handling info for a given vehicle, so it will drive more aggressively or conservatively than normal vehicles of that type

## HandlingOverrideHash Values:
| Value | Name |
| --- | --- |
| -2056575896 | Crap |
| -1532864817 | Sports Car |
| -1103972294 | Average |
| 1115750597 | Truck |


HandlingOverrideHash takes a member of the enum HANDLING_INFOS, defined above

