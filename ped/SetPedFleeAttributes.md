---
ns: PED
aliases: ["0x70a2d1137c8ed7c9"]
---
## SET_PED_FLEE_ATTRIBUTES

```c
// 0x70A2D1137C8ED7C9
void SET_PED_FLEE_ATTRIBUTES(Ped ped, int FleeAttribute, bool ActiveSkill);
```

Activate or deactivate the flee attributes, flags can be or'ed together.

## FleeAttribute Values:
| Value | Name |
| --- | --- |
| 1 | Use Cover |
| 2 | Use Vehicle |
| 4 | Can Scream |
| 8 | Prefer Pavements |
| 16 | Wander At End |
| 32 | Look For Crowds |
| 64 | Return To Orignal Position After Flee |
| 128 | Disable Hands Up |
| 256 | Update To Nearest Hated Ped |
| 512 | Never Flee |
| 1024 | Disable Cower |
| 2048 | Disable Exit Vehicle |
| 4096 | Disable Reverse In Vehicle |
| 8192 | Disable Accelerate In Vehicle |
| 16384 | Disable Flee From Indirect Threats |
| 32768 | Cower Instead Of Flee |
| 65536 | Force Exit Vehicle |
| 131072 | Disable Hesitate In Vehicle |
| 262144 | Disable Ambient Clips |


FLEE_ATTRIBUTES are in commands_ped.sch

