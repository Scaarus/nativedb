---
ns: PED
aliases: ["0x5e29243fb56fc6d4"]
---
## CLEAR_RELATIONSHIP_BETWEEN_GROUPS

```c
// 0x5E29243FB56FC6D4
void CLEAR_RELATIONSHIP_BETWEEN_GROUPS(int RelationshipType, Hash relGroup, Hash otherRelGroup);
```

Removes the relationship between rel groups.

## RelationshipType Values:
| Value | Name |
| --- | --- |
| 0 | Respect |
| 1 | Like (1) |
| 2 | Ignore (2) |
| 3 | Dislike (3) |
| 4 | Wanted (4) |
| 5 | Hate (5) |
| 6 | Dead (6) |
| 255 | None |


RELATIONSHIP_TYPE is am enum list in commands_ped.sch, REL_GROUP_HASH is an enum list in generic.sch

