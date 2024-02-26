---
ns: FIRE
aliases: ["0x6b83617e04503888"]
---
## START_SCRIPT_FIRE

```c
// 0x6B83617E04503888
Fire START_SCRIPT_FIRE(Vector3 Pos, int GenerationsAllowed, bool isPetrolFire);
```

Creates a fire at the given coords.

X, Y, Z are FLOATs FireID should be declared as a FIRE_INDEX.

These will be ignored by the fire brigade. Only the player can extinguish a script-created fire. A script-created fire must be [REMOVE_SCRIPT_FIRE](#_0x7FF548385680673F) once and only once.

