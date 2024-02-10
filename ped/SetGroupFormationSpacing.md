---
ns: PED
aliases: ["0x1d9d45004c28c916"]
---
## SET_GROUP_FORMATION_SPACING

```c
// 0x1D9D45004C28C916
void SET_GROUP_FORMATION_SPACING(Group group, float Spacing, float AdjustSpeedMinDist, float AdjustSpeedMaxDist);
```

Sets the spacing which the group formation is currently using.

Spacing = space between peds AdjustSpeedMinDist = distance from spacing position at which ped slows down (leave at -1.0 if not sure) AdjustSpeedMaxDist = distance from spacing position at which ped speeds up (leave at -1.0 if not sure)

It is only valid for one script to do this at a time!

