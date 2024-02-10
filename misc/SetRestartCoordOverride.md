---
ns: MISC
aliases: ["0x706b5edcaa7fa663"]
---
## SET_RESTART_COORD_OVERRIDE

```c
// 0x706B5EDCAA7FA663
void SET_RESTART_COORD_OVERRIDE(Vector3 Position, float Heading);
```

Ses a point where the player will restarted which overrides the defaults.

In some missions, you might want to restart the player at the point on the map where the mission is started. If this command is called then the next time the player is restarted, he will be positioned at this point rather than at the closest hospital or police restart point. Z will be calculated automatically if you give it a value of –100.0 or below. When the player restarts, his heading will be set according to PlayerHeading.

