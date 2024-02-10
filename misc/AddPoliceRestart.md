---
ns: MISC
aliases: ["0x452736765b31fc4b"]
---
## ADD_POLICE_RESTART

```c
// 0x452736765B31FC4B
Police_Restart ADD_POLICE_RESTART(Vector3 Position, float Heading, int WhenToUse);
```

Adds a coord where the player will be restarted after he has been arrested.

Currently, a maximum of 10 of each type of restart point can be defined on the map, but this can be increased if necessary. Z will be calculated automatically if you give it a value of –100.0 or below. The player will also be given the correct heading when he is restarted.

