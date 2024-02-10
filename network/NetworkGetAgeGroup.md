---
ns: NETWORK
aliases: ["0x9614b71f8adb982b"]
---
## NETWORK_GET_AGE_GROUP

```c
// 0x9614B71F8ADB982B
rl_agegroup NETWORK_GET_AGE_GROUP();
```

```
PURPOSE On xbox builds gets age group defined in ENUM RL_AGEGROUP. PS3 builds will return: RL_AGEGROUP_CHILD if age restrictions are set and the age is < MIN_AGE_RATING RL_AGEGROUP_ADULT if the age is >= MIN_AGE_RATING RL_AGEGROUP_INVALID for all other situations. NOTE: RL_AGEGROUP_TEEN is not returned on PS3

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 244 | Pending Age Group Is Being Retrieved. |
| 245 | Child |
| 246 | Teen |
| 247 | Adult |
```
