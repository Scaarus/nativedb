---
ns: TASK
aliases: ["0x88e32db8c1a4aa4b"]
---
## SET_PED_PATH_CLIMB_COST_MODIFIER

```c
// 0x88E32DB8C1A4AA4B
void SET_PED_PATH_CLIMB_COST_MODIFIER(Ped ped, float fClimbModifier);
```

Sets a multiplier to the cost function which decides whether a ped should climb whilst navigating Default value is 1.0 which means the ped behaves as normal The lower the value, the more likely a ped is to use a climb. At 0.5 the ped will be twice as likely to climb as usual At 0.0 the ped will climb just as likely as walk, even for the smallest movements (so don't use a value this low!) At 2.0 the ped will be half as likely to use a climb Etc, etc.. Be sure to set this back to 1.0 after use, or peds will behave strangely even after the mission ends.

