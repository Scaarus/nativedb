---
ns: MISC
aliases: ["0x1f464ef988465a81"]
---
## ADD_HOSPITAL_RESTART

```c
// 0x1F464EF988465A81
Hospital_Restart ADD_HOSPITAL_RESTART(Vector3 Position, float Heading, int WhenToUse);
```

Adds a coord where the player will be restarted after he has been killed.

Currently, a maximum of 10 of each type of restart point can be defined on the map, but this can be increased if necessary. Z will be calculated automatically if you give it a value of –100.0 or below. The player will also be given the correct heading when he is restarted.

