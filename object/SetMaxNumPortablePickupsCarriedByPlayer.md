---
ns: OBJECT
aliases: ["0x0bf3b3bd47d79c08"]
---
## SET_MAX_NUM_PORTABLE_PICKUPS_CARRIED_BY_PLAYER

```c
// 0x0BF3B3BD47D79C08
void SET_MAX_NUM_PORTABLE_PICKUPS_CARRIED_BY_PLAYER(int MaxPickups);
```

Sets the maximum number of portable pickups that the local player can carry. If the local player is carrying some pickups when you call this, he will drop some if he has too many. If modelName is 0, MaxPickups is the total number of portable pickups allowed to be carried of any type

