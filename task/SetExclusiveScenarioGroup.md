---
ns: TASK
aliases: ["0x535e97e1f7fc0c6a"]
---
## SET_EXCLUSIVE_SCENARIO_GROUP

```c
// 0x535E97E1F7FC0C6A
void SET_EXCLUSIVE_SCENARIO_GROUP(string scenarioGroupName);
```

Specify a particular group that should be the only scenario group that should be enabled (scenarios that are not in any group will also be considered disabled). There can only be one of these, using the command again will replace any previously set exclusive group. Note that this command does not change the regular enableddisabled state of the group, so you may also need to enable your group with [SET_SCENARIO_GROUP_ENABLED](#_0x02C8E5B49848664E) in order for it to work. NOTE: This now works like a reset flag and must be continually set every frame the scenario group ought to be exlusive!

