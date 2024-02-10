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
| 119 | Like 1 |
| 120 | Ignore 2 |
| 121 | Dislike 3 |
| 122 | Wanted 4 |
| 123 | Hate 5 |
| 124 | Dead 6 |
| 255 | None |


RELATIONSHIP_TYPE is am enum list in commands_ped.sch, REL_GROUP_HASH is an enum list in generic.sch

