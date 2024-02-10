---
ns: PED
aliases: ["0x84a2dd9ac37c35c1"]
---
## IS_PED_INJURED

```c
// 0x84A2DD9AC37C35C1
bool IS_PED_INJURED(Ped ped);
```

Checks the ped status is injured. Should be used in the majority of checks on a ped.

This check should be used on a ped to determine if ped is able to do anything in the game ie run a task. The game will assert if to you try to give an injured ped a task. This command will return true if the ped is dead as well The IS_ENTITY_DEAD command should be used only if you want to specifically know that the ped is dead. i.e. remove a blip, set the dead ped coords.

