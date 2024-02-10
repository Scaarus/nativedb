---
ns: STREAMING
aliases: ["0xbb7454baff08fe25"]
---
## SET_FOCUS_POS_AND_VEL

```c
// 0xBB7454BAFF08FE25
void SET_FOCUS_POS_AND_VEL(Vector3 pos, Vector3 vel);
```

The game focus is used for loading map data, collisions, object population etc. This command overrides it for the specified position and velocity

pos (position in world, vel(velocity to use for ped & vehicle population)

Overrides the game focus and sets it to specified position and velocity

